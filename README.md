CKEditor 5 classic editor build
========================================

## Documentation

To add or remove plugins:

1. Edit the file `src/ckeditor.js` and add (or remove) the plugins you need (or don't need). You can also define the default configuration for the editor.
2. When the new configuration is finished, save and run `yarn run build` to build the project.
3. Save, commit and push the code to the repository
4. In the Scayla app, in `package.json`, change the `commit id` of the `ckeditor` package to the newest `commit id`.
5. Run `npm install` in Scayla.

## License

Licensed under the terms of [GNU General Public License Version 2 or later](http://www.gnu.org/licenses/gpl.html). For full details about the license, please check the `LICENSE.md` file or [https://ckeditor.com/legal/ckeditor-oss-license](https://ckeditor.com/legal/ckeditor-oss-license).
