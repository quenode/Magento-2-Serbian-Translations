## Magento 2 Serbian (Latin) Language Pack

![Serbian (Latin) language pack](https://github.com/quenode/Magento-2-Serbian-Translations)

## Overview

1. Language Package Process
2. Install Serbian (Latin) Language Pack
3. How to active Serbian (Latin) language pack
4. How to contribute
5. Supported Magento versions
6. Notes
7. Language package authors

## 1. Language Package Process

This is status of Serbian (Latin) Language Pack, you can see how many percentage of this project has been done.

![Serbian (Latin) language pack process](https://progress-bar.dev/60/?title=completed&width=200)

It is not fully translated? Feel free to contribute:
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/quenode/Magento-2-Serbian-Translations): It's faster, our team will approve it after you send pull request.

## 2. How to Install Serbian (Latin) Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Serbian (Latin) language pack via composer is never easier.

**Install Serbian (Latin) pack**:

```
composer require clarus/language-sr-latn-rs
php bin/magento setup:static-content:deploy sr_Latn_RS
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

**Update Serbian (Latin) pack**:

```
composer update clarus/language-sr-latn-rs
php bin/magento setup:static-content:deploy sr_Latn_RS
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Serbian (Latin) language pack
- Step 2: Unzip Serbian (Latin) pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Serbian (Latin) language pack

You can download the language pack from [https://github.com/quenode/Magento-2-Serbian-Translations](https://github.com/quenode/Magento-2-Serbian-Translations)

#### Step 2: Unzip Serbian (Latin) pack

Unzip the Serbian (Latin) language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip master.zip app/i18n/clarus/
```

Rename folder `Magento-2-Serbian-Translations` to `sr_latn_rs`.

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

```
php bin/magento cache:flush
```

### ✓ Method #3. Download and install manually (Not recommended)

To download and install Serbian (Latin) pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/quenode/Magento-2-Serbian-Translations/archive/master.zip)
- [Download .tar.gz](https://github.com/quenode/Magento-2-Serbian-Translations/tarball/master)

#### Step 2: Unzip and upload

Unzip the compressed file and upload file `master.zip` into `app/i18n/clarus/sr_latn_rs/`

This language pack code is: **sr_Latn_RS**

#### Step 3: Flush cache

```
php bin/magento cache:flush
```

## 3. How to Active the Serbian (Latin) language pack 

Now time to active the Serbian (Latin) language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`

Select `Serbian (Latin) (sr_Latn_RS)` and save configuration.

## 4. How to contribute

Contribute to this language at :
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/quenode/Magento-2-Serbian-Translations): It's faster, our team will approve it after you send pull request.

## 5. Supported Magento versions

It supports all Magento 2 versions include Magento 2 Open Source (Community), Magento 2 Commerce (EE), Magento Cloud, Magento B2B, Magento MSI.

- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x
- Magento v2.3.x
- Magento v2.4.x

## 6. Notes 

- This project contains 9,157 real translations sourced from the Magento 2 Crowdin project (master_sr-CS.xliff).
- No identity entries — every string in this pack is a real translation.
- Untranslated strings fall back to English naturally.
- Any question, issue please [create a new issue](https://github.com/quenode/Magento-2-Serbian-Translations/issues/new)

## 7. Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Magento Community
- Language package built by [Clarus d.o.o.](https://github.com/quenode/Magento-2-Serbian-Translations)

## 8. References 

- https://github.com/quenode/Magento-2-Serbian-Translations
- https://crowdin.com/project/magento-2
