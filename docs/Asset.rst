======
Asset
======

buyAsset
=========

Parameters
~~~~~~~~~~~
- Asset ID

Output
~~~~~~~
- sudbhdjiolsk

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie')
   rbx.Asset.buyAsset(id)

getAssetInfo
=============

Parameters
~~~~~~~~~~~
- Asset ID

Output
~~~~~~~
- TargetId
- ProductType
- AssetId
- ProductId
- Name
- Description
- AssetTypeId
- Creator
   - Id
   - Name
   - CreatorType
   - CreatorTargetId
- IconImageAssetId
- Created
- Updated
- PriceInRobux
- PriceInTickets
- Sales
- IsNew
- IsForSale
- IsPublicDomain
- IsLimited
- IsLimitedUnique
- Remaining
- MinimumMembershipLevel
- ContentRatingTypeId

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie')
   rbx.Asset.getAssetInfo(id)

getOutfits
===========

Parameters
~~~~~~~~~~~
- None

Output
~~~~~~~
- data
- total

Example
~~~~~~~~
.. code-block:: python
   
   import robloxapi;
   rbx = robloxapi.client('Cookie')
   rbx.Asset.getOutfits()

searchCatalog
==============

Parameters
~~~~~~~~~~~
- Keyword

Output
~~~~~~~
- Items
   - ItemTargetId
   - ItemType
   - AssetId
   - Name
   - AbsoluteUrl
   - Price
   - BestPrice
   - Remaining
   - HasSecondaryInfo
   - NoPriceText
   - IsFree
   - Creator
      - Id
      - Name
      - Type
      - CreatorProfileLink
   - AssetRestrictionInfo
      - TooltipText
      - CssTag
      - LoadAssetRestrictionIconCss
      - HasTooltip
   - AssetStatusIcon
   - Thumbnail
      - Final
      - Url
      - RetryUrl
      - IsApproved

wearOutfit
===========

Parameters
~~~~~~~~~~~
- Outfit ID

Output
~~~~~~~
- success

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie')
   rbx.Asset.wearOutfit(id)
