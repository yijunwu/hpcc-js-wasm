INCLUDE_DIRECTORIES(
    ${GRAPHVIZ_LIB_DIR}/circogen
    ${GRAPHVIZ_LIB_DIR}/cdt
    ${GRAPHVIZ_LIB_DIR}/cgraph
    ${GRAPHVIZ_LIB_DIR}/common
    ${GRAPHVIZ_LIB_DIR}/gvc
    ${GRAPHVIZ_LIB_DIR}/neatogen
    ${GRAPHVIZ_LIB_DIR}/pack
    ${GRAPHVIZ_LIB_DIR}/pathplan
    ${GRAPHVIZ_LIB_DIR}/sparse
)

ADD_LIBRARY(circogen STATIC
    # Source files
    ${GRAPHVIZ_LIB_DIR}/circogen/block.c
    ${GRAPHVIZ_LIB_DIR}/circogen/blockpath.c
    ${GRAPHVIZ_LIB_DIR}/circogen/blocktree.c
    ${GRAPHVIZ_LIB_DIR}/circogen/circpos.c
    ${GRAPHVIZ_LIB_DIR}/circogen/circular.c
    ${GRAPHVIZ_LIB_DIR}/circogen/circularinit.c
    ${GRAPHVIZ_LIB_DIR}/circogen/deglist.c
    ${GRAPHVIZ_LIB_DIR}/circogen/edgelist.c
    ${GRAPHVIZ_LIB_DIR}/circogen/nodelist.c
    ${GRAPHVIZ_LIB_DIR}/circogen/nodeset.c
)

