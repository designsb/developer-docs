

..  list-table::
  :widths: 30 8 40
  :header-rows: 1
  :class: parameters

  * - Field
    - Name in Reports
    - Description

  * - advertiser_campaign_id
    - Advertiser Campaign ID (Invoca ID)
    - The Invoca identifier of the campaign.

  * - advertiser_campaign_id_from_network
    - Advertiser Campaign ID
    - The Campaign ID from the network as set on the advertiser campaign.

  * - advertiser_campaign_name
    - Advertiser Campaign
    - Name of the campaign.

  * - advertiser_id
    - Advertiser ID (Invoca ID)
    - The Invoca identifier of the advertiser

  * - advertiser_id_from_network
    - Advertiser ID
    - Advertiser ID from the network as set on the Invoca advertiser.

  * - advertiser_name
    - Advertiser
    - Name of the advertiser.

  * - affiliate_payout_localized
    - Earnings
    - Amount paid out to the affiliate

  * - call_result_description_detail
    - Call Result
    - Status of the transaction

  * - call_source_description
    - Source
    - Source of the transaction

  * - city
    - City
    - City where transaction originated

  * - complete_call_id
    - Call Record ID
    - Globally unique identifier for the call this transaction is part of. Up-to 32 character string, can contain alphanumeric characters (i.e. 0-9A-Z) and the -.

  * - connect_duration
    - Connected Duration
    - Duration in seconds that the call that was connected to the call center.

  * - corrected_at
    - Corrected At
    - [Correction only] Date and time the transaction was corrected, in user's time zone, followed by offset from GMT.

  * - corrects_transaction_id
    - Corrects Call
    - [Correction only] Id of the original transaction that this transaction updates. Values in this row are the corrected ones and should replace the original values. Same format as transaction_id. Up-to 32 character string, can contain alphanumeric characters (i.e. 0-9A-Z) and the -.

  * - duration
    - Total Duration
    - Duration of the call in seconds. Includes any time spent in an IVR tree before transferring to the call center.

  * - ivr_duration
    - IVR Duration
    - Duration in seconds that the call spent in the IVR tree.

  * - keypress_1
    - Key 1
    - Name of the first key that was pressed

  * - keypress_2
    - Key 2
    - Name of the second key that was pressed

  * - keypress_3
    - Key 3
    - Name of the third key that was pressed

  * - keypress_4
    - Key 4
    - Name of the fourth key that was pressed

  * - keypresses
    - Keypresses
    - List of unique keynames that were pressed during the call

  * - matching_affiliate_payout_policies
    - Matching Affiliate Payout Policies
    - List of affiliate policies that matched (base, bonus1, bonus2, etc.) to determine the affiliate payout, separated by +. For example, base+bonus2. Note that if there was any affiliate payout, this field guaranteed to start with base.

  * - media_type
    - Media Type
    - Media type of the transaction source

  * - mobile
    - Phone Type
    - Landline or Mobile or empty string if type is unknown

  * - notes
    - Notes
    - Free-form notations on transaction

  * - opt_in_SMS
    - Opt In Sms
    - Whether the caller opted in to receive an SMS promotion.

  * - original_order_id
    - Order ID
    - [Sales reporting only] Id of the original transaction that this row is in reference to. Up-to 32 character string, can contain alphanumeric characters (i.e. 0-9A-Z) and the -.

  * - payout_conditions
    - Payout Conditions
    - Base condition with { highlighting } around the term(s) that disqualified affiliate payout. For example: duration > 1 min and {in_region}

  * - promo_line_description
    - Promo Number Description
    - Additional details about the transaction source

  * - qualified_regions
    - Qualified Regions
    - The list of regions that that the caller matched

  * - region
    - Region
    - Region (state, province or country) where transaction originated

  * - start_time_local
    - Call Start Time
    - Start of the call in the API user's time zone, followed by offset from GMT.

  * - start_time_utc
    - Call Start Time (UTC timestamp)
    - Start of the call in milliseconds since Jan 1, 1970. Divide by 1000 to get Unix epoch time.

  * - start_time_xml
    - Call Start Time (XML formatted)
    - Start of the call in Soap XML formatted time.

  * - start_time_network_timezone
    - Call Start Time Network Timezone
    - Start of the call in the networks's time zone, followed by offset from GMT.

  * - start_time_network_timezone_xml
    - Call Start Time Network Timezone (XML formatted)
    - Start of the call in the network's time zone in Soap XML formatted time.

  * - syndicated_ident
    - Syndicated ID
    - The syndicated id for this call.  Uniquely identifies syndication sources for a campaign.

  * - transaction_id
    - Transaction ID
    - Globally unique identifier for this transaction. Up-to 32 character string, can contain alphanumeric characters (i.e. 0-9A-Z) and the -. This is the Primary Key of the results.

  * - transaction_type
    - Type
    - The type of transaction - Call, Reported Conversion or Signal.

  * - transfer_from_type
    - Transfer Type
    - Where the call came from

  * - verified_zip
    - Verified Zip Code
    - Zip Code entered by callers when prompted during call treatment

  * - virtual_line_id
    - Promo Number ID
    - The Promo Number ID from the network
