include_directories(../utils/
                    ../utils/htslib/
                    ../utils/bedtools/lineFileUtilities/
                    ../utils/bedtools/fileType/
                    ../utils/bedtools/gzstream/
                    ../utils/bedtools/bedFile/)
add_library(gtf
    gtf_parser.cc
    gtf_utils.cc)

