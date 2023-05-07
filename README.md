# Sign Commit
Uses [crazy-max/ghaction-import-gpg@v5](https://github.com/marketplace/actions/import-gpg) to sign commits and tags.

## Usage
```yml
uses: mnrendra/sign-commit@v1
with:
  gpg_private_key: ${{ secrets.GPG_PRIVATE_KEY }}
  # @description: GPG Private Key.
  # @type: string
  # @required: true

  passphrase: ${{ secrets.PASSPHRASE }}
  # @description: Passphrase.
  # @type: string
  # @required: true
```

## Author
[@mnrendra](https://github.com/mnrendra)
