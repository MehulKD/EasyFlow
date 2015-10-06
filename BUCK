java_library(
	name = 'src',
	srcs = glob(['src/main/java/**/*.java']),
	deps = [
		'//.okbuck/EasyFlow:all-jars',
	],
	exported_deps = [
		'//.okbuck/EasyFlow:all-jars',
	],
	visibility = ['PUBLIC'],
	annotation_processors = [
	],
	annotation_processor_deps = [
		'//.okbuck/EasyFlow:all-jars',
		'//.okbuck/annotation_processor_deps:all-jars',
	],
)

project_config(
	src_target = '//EasyFlow:src',
	src_roots = ['src/main/java'],
)
