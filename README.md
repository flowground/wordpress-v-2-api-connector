# ![LOGO](logo.png) Wordpress v2 API **flow**ground Connector

## Description

A generated **flow**ground connector for the Wordpress v2 API API (version 0.1.1).

Generated from: http://localhost<br/>
Generated at: 2019-07-31T18:39:18+03:00

## API Description

Wordpress v2 API<br/>

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List Posts
> Scope under which the request is made; determines fields present in response.<br/>

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Create Post

### Get Single Post

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Update Single Post

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Delete Single Post

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `force` - _optional_ - Whether to bypass trash and force deletion.<br/>

### Get post revisions

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Get single post revisions

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `revisionid` - _required_ - Id of revision<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Delete single post revisions

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `revisionid` - _required_ - Id of revision<br/>

### List Pages
> Scope under which the request is made; determines fields present in response.<br/>

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Create Page

### Get Single Page

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Update Single Page

#### Input Parameters
* `id` - _required_ - Id of object<br/>

### Delete Single Page

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `force` - _optional_ - Whether to bypass trash and force deletion.<br/>

### List Media
> Scope under which the request is made; determines fields present in response.<br/>

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Create Media

### Get Single Media

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Update Single Media

#### Input Parameters
* `id` - _required_ - Id of object<br/>

### Delete Single Media

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `force` - _optional_ - Whether to bypass trash and force deletion.<br/>

### List Type
> Scope under which the request is made; determines fields present in response.<br/>

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Get Single Type

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### List Status
> Scope under which the request is made; determines fields present in response.<br/>

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Get Single Status

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### List Comments
> Scope under which the request is made; determines fields present in response.<br/>

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Create Comment

### Get Single Comment

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Update Single Comment

#### Input Parameters
* `id` - _required_ - Id of object<br/>

### Delete Single Comment

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `force` - _optional_ - Whether to bypass trash and force deletion.<br/>

### List Taxonomy

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Get Single Taxonomy

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### List categories

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Create Category

### Get Single Category

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Update Single Category

#### Input Parameters
* `id` - _required_ - Id of object<br/>

### Delete Single Category

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `force` - _optional_ - Whether to bypass trash and force deletion.<br/>

### List Tags

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Create Tag

### Get Single Tag

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Update Single Tag

#### Input Parameters
* `id` - _required_ - Id of object<br/>

### Delete Single Tag

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `force` - _optional_ - Whether to bypass trash and force deletion.<br/>

### List Tags

#### Input Parameters
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Create User

### Get Single User

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Update Single User

#### Input Parameters
* `id` - _required_ - Id of object<br/>

### Delete Single User

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `force` - _optional_ - Whether to bypass trash and force deletion.<br/>

### List User Metadata

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Create User Metadata

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `key` - _required_ - Key of meta data value<br/>
* `value` - _required_ - Value of meta data<br/>

### Get Single User Metadata

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `metaid` - _required_ - Id of meta data<br/>
* `context` - _optional_ - Scope under which the request is made; determines fields present in response.<br/>
    Possible values: view, embed, edit.

### Update Single User Metadata

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `metaid` - _required_ - Id of meta data<br/>
* `key` - _required_ - Key of meta data value<br/>
* `value` - _required_ - Value of meta data<br/>

### Delete Single User

#### Input Parameters
* `id` - _required_ - Id of object<br/>
* `metaid` - _required_ - Id of meta data<br/>
* `force` - _optional_ - Whether to bypass trash and force deletion.<br/>

## License

**flow**ground :- Telekom iPaaS / wordpress-v-2-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
