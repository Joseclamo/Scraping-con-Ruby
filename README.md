# Scraping-with-Ruby 💪

PoC of a Ruby Script to know the last block of the Ethereum network according to
[Etherscan](https://etherscan.io/), using the Nokogiri gem, the used OS is *Ubuntu 16.04LTS*.

*Nokogiri* allows us to parse *HTML, XML, SAX...* this is the link to [rubygems]
(https://rubygems.org/gems/nokogiri) and to [Github](https://github.com/sparklemotion/nokogiri/).

To install the gem it is only necessary to write the following commands in the console:
  > sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev
  > gem install nokogiri

To execute it, we will write in the console:
  > ruby scrap-en.rb
