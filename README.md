[![npm version](https://badge.fury.io/js/entu-cms.svg)](https://badge.fury.io/js/entu-cms)
[![Dependency Status](https://david-dm.org/argoroots/entu-cms.svg)](https://david-dm.org/argoroots/entu-cms)

## Entu CMS

Simple ([Jade](http://jade-lang.com)) file based CMS with multilanguage support


### Installation

    npm install -g npm-cms


### Usage

    npm-cms ./config.yaml


#### Example config.yaml

    locales:
      - en
      - et
      - ru
    source: ./source
    build: ./build
    timeout: 10
    jade:
      basedir: ./source/_templates
      pretty: false
