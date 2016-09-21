# Bazel build file for cppjieba

licenses(["notice"])

cc_library(
    name = "cppjieba",
    srcs = [
        "limonp/ArgvContext.hpp",
        "limonp/BlockingQueue.hpp",
        "limonp/BoundedBlockingQueue.hpp",
        "limonp/BoundedQueue.hpp",
        "limonp/Closure.hpp",
        "limonp/Colors.hpp",
        "limonp/Condition.hpp",
        "limonp/Config.hpp",
        "limonp/FileLock.hpp",
        "limonp/ForcePublic.hpp",
        "limonp/LocalVector.hpp",
        "limonp/Logging.hpp",
        "limonp/Md5.hpp",
        "limonp/MutexLock.hpp",
        "limonp/NonCopyable.hpp",
        "limonp/StdExtension.hpp",
        "limonp/StringUtil.hpp",
        "limonp/Thread.hpp",
        "limonp/ThreadPool.hpp",
    ],
    hdrs = [
        "cppjieba/DictTrie.hpp",
        "cppjieba/FullSegment.hpp",
        "cppjieba/HMMModel.hpp",
        "cppjieba/HMMSegment.hpp",
        "cppjieba/Jieba.hpp",
        "cppjieba/KeywordExtractor.hpp",
        "cppjieba/MPSegment.hpp",
        "cppjieba/MixSegment.hpp",
        "cppjieba/PosTagger.hpp",
        "cppjieba/PreFilter.hpp",
        "cppjieba/QuerySegment.hpp",
        "cppjieba/SegmentBase.hpp",
        "cppjieba/SegmentTagged.hpp",
        "cppjieba/TextRankExtractor.hpp",
        "cppjieba/Trie.hpp",
        "cppjieba/Unicode.hpp",
    ],
    includes = [],
    visibility = ["//visibility:public"],
)

filegroup(
    name = "dict",
    srcs = glob([
        "dict/*.*",
        "dict/**/*.*",
    ]),
)
