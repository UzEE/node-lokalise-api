[lokalise](../README.md) > ["collections/translations"](../modules/_collections_translations_.md) > [Translations](../classes/_collections_translations_.translations.md)

# Class: Translations

## Hierarchy

 [BaseCollection](_collections_base_collection_.basecollection.md)

**↳ Translations**

## Index

### Properties

* [elementClass](_collections_translations_.translations.md#elementclass)
* [endpoint](_collections_translations_.translations.md#endpoint)
* [prefixURI](_collections_translations_.translations.md#prefixuri)
* [rootElementName](_collections_translations_.translations.md#rootelementname)

### Methods

* [create](_collections_translations_.translations.md#create)
* [createPromise](_collections_translations_.translations.md#createpromise)
* [delete](_collections_translations_.translations.md#delete)
* [get](_collections_translations_.translations.md#get)
* [handleReject](_collections_translations_.translations.md#handlereject)
* [list](_collections_translations_.translations.md#list)
* [populateArrayFromJson](_collections_translations_.translations.md#populatearrayfromjson)
* [populateObjectFromJson](_collections_translations_.translations.md#populateobjectfromjson)
* [returnBareJSON](_collections_translations_.translations.md#returnbarejson)
* [update](_collections_translations_.translations.md#update)

---

## Properties

<a id="elementclass"></a>

### `<Static>``<Protected>` elementClass

**● elementClass**: *`any`* =  null

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[elementClass](_collections_base_collection_.basecollection.md#elementclass)*

*Defined in [collections/base_collection.ts:8](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L8)*

___
<a id="endpoint"></a>

### `<Static>``<Protected>` endpoint

**● endpoint**: *`string`* =  null

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[endpoint](_collections_base_collection_.basecollection.md#endpoint)*

*Defined in [collections/base_collection.ts:6](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L6)*

___
<a id="prefixuri"></a>

### `<Static>``<Protected>` prefixURI

**● prefixURI**: *`string`* = "projects/{!:project_id}/translations/{:id}"

*Overrides [BaseCollection](_collections_base_collection_.basecollection.md).[prefixURI](_collections_base_collection_.basecollection.md#prefixuri)*

*Defined in [collections/translations.ts:5](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/translations.ts#L5)*

___
<a id="rootelementname"></a>

### `<Static>``<Protected>` rootElementName

**● rootElementName**: *`string`* = "translations"

*Overrides [BaseCollection](_collections_base_collection_.basecollection.md).[rootElementName](_collections_base_collection_.basecollection.md#rootelementname)*

*Defined in [collections/translations.ts:4](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/translations.ts#L4)*

___

## Methods

<a id="create"></a>

###  create

▸ **create**(body: *`any`*, params?: *[StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md)*): `Promise`<`any`>

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[create](_collections_base_collection_.basecollection.md#create)*

*Defined in [collections/base_collection.ts:18](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L18)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| body | `any` | - |
| `Default value` params | [StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md) |  {} |

**Returns:** `Promise`<`any`>

___
<a id="createpromise"></a>

### `<Protected>` createPromise

▸ **createPromise**(method: *`any`*, params: *`any`*, resolveFn: *`any`*, rejectFn?: *[handleReject](_collections_base_collection_.basecollection.md#handlereject)*, body?: *`any`*, uri?: *`any`*): `Promise`<`any`>

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[createPromise](_collections_base_collection_.basecollection.md#createpromise)*

*Defined in [collections/base_collection.ts:55](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L55)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| method | `any` | - |
| params | `any` | - |
| resolveFn | `any` | - |
| `Default value` rejectFn | [handleReject](_collections_base_collection_.basecollection.md#handlereject) |  this.handleReject |
| `Default value` body | `any` |  null |
| `Default value` uri | `any` |  null |

**Returns:** `Promise`<`any`>

___
<a id="delete"></a>

###  delete

▸ **delete**(id: *`any`*, params?: *[StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md)*): `Promise`<`any`>

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[delete](_collections_base_collection_.basecollection.md#delete)*

*Defined in [collections/base_collection.ts:27](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L27)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| id | `any` | - |
| `Default value` params | [StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md) |  {} |

**Returns:** `Promise`<`any`>

___
<a id="get"></a>

###  get

▸ **get**(id: *`any`*, params?: *[StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md)*, body?: *`any`*): `Promise`<`any`>

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[get](_collections_base_collection_.basecollection.md#get)*

*Defined in [collections/base_collection.ts:10](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L10)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| id | `any` | - |
| `Default value` params | [StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md) |  {} |
| `Default value` body | `any` |  null |

**Returns:** `Promise`<`any`>

___
<a id="handlereject"></a>

### `<Protected>` handleReject

▸ **handleReject**(data: *`any`*): `any`

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[handleReject](_collections_base_collection_.basecollection.md#handlereject)*

*Defined in [collections/base_collection.ts:51](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L51)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| data | `any` |

**Returns:** `any`

___
<a id="list"></a>

###  list

▸ **list**(params?: *[StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md)*): `Promise`<`any`[]>

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[list](_collections_base_collection_.basecollection.md#list)*

*Defined in [collections/base_collection.ts:14](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L14)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Default value` params | [StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md) | {} |

**Returns:** `Promise`<`any`[]>

___
<a id="populatearrayfromjson"></a>

### `<Protected>` populateArrayFromJson

▸ **populateArrayFromJson**(json: *`Array`<`any`>*): `this`[]

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[populateArrayFromJson](_collections_base_collection_.basecollection.md#populatearrayfromjson)*

*Defined in [collections/base_collection.ts:37](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L37)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| json | `Array`<`any`> |

**Returns:** `this`[]

___
<a id="populateobjectfromjson"></a>

### `<Protected>` populateObjectFromJson

▸ **populateObjectFromJson**(json: *`Object`*): `this`

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[populateObjectFromJson](_collections_base_collection_.basecollection.md#populateobjectfromjson)*

*Defined in [collections/base_collection.ts:32](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L32)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| json | `Object` |

**Returns:** `this`

___
<a id="returnbarejson"></a>

### `<Protected>` returnBareJSON

▸ **returnBareJSON**(json: *`any`*): `any`

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[returnBareJSON](_collections_base_collection_.basecollection.md#returnbarejson)*

*Defined in [collections/base_collection.ts:47](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L47)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| json | `any` |

**Returns:** `any`

___
<a id="update"></a>

###  update

▸ **update**(id: *`any`*, body: *`any`*, params?: *[StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md)*): `Promise`<`any`>

*Inherited from [BaseCollection](_collections_base_collection_.basecollection.md).[update](_collections_base_collection_.basecollection.md#update)*

*Defined in [collections/base_collection.ts:22](https://github.com/lokalise/node-lokalise-api/blob/7c5421a/src/collections/base_collection.ts#L22)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| id | `any` | - |
| body | `any` | - |
| `Default value` params | [StandartParams](../interfaces/_interfaces_standart_params_.standartparams.md) |  {} |

**Returns:** `Promise`<`any`>

___

