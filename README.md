# tagm8

git like command-line client for tagm8-vault

exploits GLI which assumes ruby gems distribution

To run in development use:

1. make sure tagm8-vault is listening for a connection
2. cd (path to project root)
2. bundle install
3. bundle exec tagm8 (command) eg. bundle exec tagm8 list_tags --details

Please refer to [tagm8-vault wiki](https://github.com/metafacets/tagm8-vault/wiki) for further documentation of this and the accompanying tagm8-vault.