[alchemy-sdk](../README.md) / [Exports](../modules.md) / TransferredNft

# Interface: TransferredNft

NFT with extra data for a single NFT that was transferred or minted.

## Hierarchy

- [`Nft`](Nft.md)

  ↳ **`TransferredNft`**

## Table of contents

### Properties

- [blockNumber](TransferredNft.md#blocknumber)
- [contract](TransferredNft.md#contract)
- [description](TransferredNft.md#description)
- [from](TransferredNft.md#from)
- [media](TransferredNft.md#media)
- [metadataError](TransferredNft.md#metadataerror)
- [rawMetadata](TransferredNft.md#rawmetadata)
- [spamInfo](TransferredNft.md#spaminfo)
- [timeLastUpdated](TransferredNft.md#timelastupdated)
- [title](TransferredNft.md#title)
- [to](TransferredNft.md#to)
- [tokenId](TransferredNft.md#tokenid)
- [tokenType](TransferredNft.md#tokentype)
- [tokenUri](TransferredNft.md#tokenuri)
- [transactionHash](TransferredNft.md#transactionhash)

## Properties

### blockNumber

• **blockNumber**: `string`

The block number as a hex string of when the transfer or mint occurred.

#### Defined in

[src/types/types.ts:1045](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/types/types.ts#L1045)

___

### contract

• **contract**: [`NftContract`](NftContract.md)

The NFT's underlying contract and relevant contract metadata.

#### Inherited from

[Nft](Nft.md).[contract](Nft.md#contract)

#### Defined in

[src/api/nft.ts:81](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L81)

___

### description

• **description**: `string`

The NFT description.

#### Inherited from

[Nft](Nft.md).[description](Nft.md#description)

#### Defined in

[src/api/nft.ts:87](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L87)

___

### from

• **from**: `string`

The address the NFT was from. For minted NFTs, this field is the set to
`0x0000000000000000000000000000000000000000`.

#### Defined in

[src/types/types.ts:1039](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/types/types.ts#L1039)

___

### media

• **media**: [`Media`](Media.md)[]

URIs for accessing the NFT's media assets.

#### Inherited from

[Nft](Nft.md).[media](Nft.md#media)

#### Defined in

[src/api/nft.ts:105](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L105)

___

### metadataError

• **metadataError**: `undefined` \| `string`

Holds an error message if there was an issue fetching metadata.

#### Inherited from

[Nft](Nft.md).[metadataError](Nft.md#metadataerror)

#### Defined in

[src/api/nft.ts:93](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L93)

___

### rawMetadata

• **rawMetadata**: `undefined` \| [`NftMetadata`](NftMetadata.md)

The raw metadata fetched from the metadata URL specified by the NFT. The
field is undefined if Alchemy was unable to fetch metadata.

#### Inherited from

[Nft](Nft.md).[rawMetadata](Nft.md#rawmetadata)

#### Defined in

[src/api/nft.ts:99](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L99)

___

### spamInfo

• `Optional` **spamInfo**: [`SpamInfo`](SpamInfo.md)

Detailed information on why an NFT was classified as spam.

#### Inherited from

[Nft](Nft.md).[spamInfo](Nft.md#spaminfo)

#### Defined in

[src/api/nft.ts:108](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L108)

___

### timeLastUpdated

• **timeLastUpdated**: `string`

When the NFT was last updated in the blockchain. Represented in ISO-8601 format.

#### Inherited from

[Nft](Nft.md).[timeLastUpdated](Nft.md#timelastupdated)

#### Defined in

[src/api/nft.ts:90](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L90)

___

### title

• **title**: `string`

The NFT title.

#### Inherited from

[Nft](Nft.md).[title](Nft.md#title)

#### Defined in

[src/api/nft.ts:84](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L84)

___

### to

• `Optional` **to**: `string`

The address the NFT was sent or minted to.

#### Defined in

[src/types/types.ts:1041](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/types/types.ts#L1041)

___

### tokenId

• **tokenId**: `string`

The NFT token ID as an integer string.

#### Inherited from

[Nft](Nft.md).[tokenId](Nft.md#tokenid)

#### Defined in

[src/api/nft.ts:65](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L65)

___

### tokenType

• **tokenType**: [`NftTokenType`](../enums/NftTokenType.md)

The type of ERC token, if known.

#### Inherited from

[Nft](Nft.md).[tokenType](Nft.md#tokentype)

#### Defined in

[src/api/nft.ts:67](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L67)

___

### tokenUri

• **tokenUri**: `undefined` \| [`TokenUri`](TokenUri.md)

URIs for accessing the NFT's metadata blob.

#### Inherited from

[Nft](Nft.md).[tokenUri](Nft.md#tokenuri)

#### Defined in

[src/api/nft.ts:102](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/api/nft.ts#L102)

___

### transactionHash

• **transactionHash**: `string`

The transaction hash where the transfer or mint occurred.

#### Defined in

[src/types/types.ts:1043](https://github.com/alchemyplatform/alchemy-sdk-js/blob/dc20ee4/src/types/types.ts#L1043)