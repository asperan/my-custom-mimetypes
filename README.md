# My custom MIME types
This repository contains the configuration files for adding some most-used extra MIME types of mine.

The configured types are in the [build script](build.gradle.kts).

The configuration is based on [mimeinfo-gradle-plugin](https://github.com/asperan/mimeinfo-gradle-plugin), so head there for documentation about the configuration of the plugin.

## Usage
To apply the configuration, run `./gradlew installMimeInfos`.

After the successful execution, you can delete any generated `.xml` file.

# License
This repository is licensed under the [MIT License](LICENSE).
