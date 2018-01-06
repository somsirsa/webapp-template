# Web Application Template

A minimal and extendable PHP and Vue application template.

## Quick usage

1. Download this repository.

2. Install dependencies:

   ```bash
   composer install
   yarn install
   ```

3. Copy `app/bootstrap/config.php.dist` to `app/bootstrap/config.php`.

4. Start webpack in "watch" or "build" mode:

   ```
   yarn run watch
   yarn run build
   ```

## Notes and tips

### Deploy

This template proposes to use really nice [PHPloy](https://github.com/banago/PHPloy)
as a deployment tool. If you use another deployment tool or method you can simply delete
`phploy.ini` from the repository root.

### Remove www, force www, force https

You can find all the rules in `public_html/.htaccess` file. Just uncomment what you need.

## Credits

[Yury Plashenkov](https://yuryplashenkov.com)

## License

This project is licensed under the [MIT license](LICENSE.md).
