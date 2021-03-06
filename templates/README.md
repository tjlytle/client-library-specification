Nexmo Client Library for [LANGUAGE]
===================================
[BADGES, BUILD STATUS, ETC]

You can use this [LANGUAGE] client library to add [Nexmo's API](#api-coverage) to your application. To use this, you'll 
need a Nexmo account. Sign up [for free at nexmo.com][signup]. 

 * [Installation](#installation)
 * [Configuration](#configuration)
 * [Usage](#usage)
 * [Examples](#examples)
 * [Coverage](#api-coverage)
 * [Contributing](#contributing) 


Installation
------------

To use the client library you'll need to have [created a Nexmo account][signup]. 

To install the [LANGUAGE] client library using [PACKAGE MANAGER]:

    COMMAND, CONFIGURATION

Alternatively you can [CLONE, DOWNLOAD]

    EXAMPLE CLONE COMMAND


Configuration
-------------
_Optional: Generally for compiled languages, how to configure for build._

To configure Nexmo [LANGUAGE] in your application:

Some step 

    EXAMPLE OF THAT STEP
    
Another step

    EXAMPLE OF THAT STEP
    
Usage
-----
To use Nexmo [LANGUAGE] in your application, create a instance of the client library using your Nexmo API credentials. 

    EXAMPLE CODE
    
### Using a Proxy
    
The client library supports passing requests through a proxy in two ways. You can change override the host and base path
used when making API requests:

    EXAMPLE CODE
    
You can also configure the client library to work with a traditional proxie server:

    EXAMPLE CODE

Examples
--------
The following examples show how to:
 * [Send a message](#sending-a-message)
 * [Receive a message](#receiving-a-message)
 * [Initiate a call](#initiating-a-call)

### Sending A Message

Use [Nexmo's SMS API][doc_sms] to send an SMS message. 

    //example code showing the client sending an SMS message, and using the response


### Receiving a Message

### Initiating a Call

### [Additional Examples]


API Coverage
------------

* Account
    * [X] Balance
    * [ ] Pricing
    * [ ] Settings
    * [ ] Top Up
    * [ ] Numbers
        * [ ] Search
        * [ ] Buy
        * [ ] Cancel
        * [ ] Update
* Number Insight
    * [ ] Basic
    * [ ] Standard
    * [ ] Advanced
    * [ ] Webhook Notification
* Verify
    * [ ] Verify
    * [ ] Check
    * [ ] Search
    * [ ] Control
* Messaging 
    * [ ] Send
    * [ ] Delivery Receipt
    * [ ] Inbound Messages
    * [ ] Search
        * [ ] Message
        * [ ] Messages
        * [ ] Rejections
    * [ ] US Short Codes
        * [ ] Two-Factor Authentication
        * [ ] Event Based Alerts
            * [ ] Sending Alerts
            * [ ] Campaign Subscription Management
* Voice
    * [ ] Create call
    * [ ] List calls
    * [ ] Get call info
    * [ ] Modify existing call
    * [ ] Stream audio to an existing call
    * [ ] Stop streaming audio to an existing call
    * [ ] Send speech to an existing call
    * [ ] Stop speech in an existing call
    * [ ] Send DTMF to an existing call
    * [ ] eventUrl webhook support
    * [ ] answerUrl webhook support
* Voice (Deprecated API)
    * [ ] Outbound Calls
    * [ ] Inbound Call
    * [ ] Text-To-Speech Call
    * [ ] Text-To-Speech Prompt

Contributing
------------

[TBD]

License
-------

This library is released under the [MIT License][license]

[create_account]: https://docs.nexmo.com/tools/dashboard#setting-up-your-nexmo-account
[signup]: https://dashboard.nexmo.com/sign-up?utm_source=DEV_REL&utm_medium=github&utm_campaign=[LANGUAGE]-client-library
[doc_sms]: https://docs.nexmo.com/api-ref/sms-api?utm_source=DEV_REL&utm_medium=github&utm_campaign=[LANGUAGE]-client-library
[license]: LICENSE.txt
