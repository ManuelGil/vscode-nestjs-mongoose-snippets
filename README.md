# NestJS Mongoose ODM Snippets for VSCode Editor

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-nestjs-mongoose-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mongoose-snippets)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-nestjs-mongoose-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mongoose-snippets)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-nestjs-mongoose-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mongoose-snippets)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-nestjs-mongoose-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-mongoose-snippets&ssr=false#review-details)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-nestjs-mongoose-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-nestjs-mongoose-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-nestjs-mongoose-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-nestjs-mongoose-snippets/blob/main/LICENSE)

Snippets for Mongoose ODM and NestJS for faster development. This extension for Visual Studio Code adds snippets for Mongoose ODM for NestJS development.

## Requirements

- VSCode 1.46.0 or later

## Usage

### Snippets

![demo](https://raw.githubusercontent.com/ManuelGil/vscode-nestjs-mongoose-snippets/main/docs/images/demo.gif)

Type part of snippet, press `Tab` or `Enter`, and the snippet unfolds. Below is a list of the most important shortcuts.

| Snippet | Purpose |
| --- | --- |
| ns_mongoose_deco_schema | @Schema() export class Document {} |
| ns_mongoose_deco_prop | @Prop() |
| ns_mongoose_inject_model | @InjectModel(...) private Model: Model<> |
| ns_mongoose_inject_connection | @InjectConnection() private connection: Connection |
| ns_mongoose_schema_types_object_id | mongoose.Schema.Types.ObjectId |
| ns_mongoose_find_one | ... = await this.Model.findOne({ ... }).exec(); |
| ns_mongoose_find_by_id | ... = await this.Model.findById(id).exec(); |
| ns_mongoose_find | ... = await this.Model.find({ ... }); |
| ns_mongoose_create | const ... = new this.Model(...);return ...; |

## Connect with me

[![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge&logo=github)](https://github.com/ManuelGil)
[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- [NestJS File Generator for VSCode](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)
- [NestJS Snippets for VSCode Editor](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
- [Angular File Generator for VSCode Editor](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)
- [React / NextJS / T3 Stack File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)
- [Nx / Angular / Nest / Next Essential Extension Pack](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nx-pack)
- [CodeIgniter 4 Snippets for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)
- [CodeIgniter 4 Spark for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-spark)
- [Moodle Pack](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-moodle-snippets)
- [Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)

## Changelog

See [CHANGELOG.md](./CHANGELOG.md)

## Authors

- **Manuel Gil** - _Owner_ - [ManuelGil](https://github.com/ManuelGil)

See also the list of [contributors](https://github.com/ManuelGil/vscode-nestjs-mongoose-snippets/contributors) who participated in this project.

## License

NestJS Mongoose ODM Snippets for VSCode is licensed under the MIT License - see the [MIT License](https://opensource.org/licenses/MIT) for details.
