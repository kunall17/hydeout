---
layout: page
title: GSOC '17
sidebar_link: true
---


# Google summer of code '17: Report

### Introduction

I worked on the react native framework, to enhance the cross platform group chat application for the orgranization **Zulip**.

I have been contributing to Zulip since my [last GSOC](./gsoc16) and it has been a great experience so far, thanks to the Zulip Organization for selecting me again.

In this course of 3 months I have done a lot of changes, implemented new features, fixed many crutial bugs, worked on not only RN but also on several other things.

### Some quick links

* [Repository link](https://github.com/zulip/zulip-mobile)
* [Pull request's](https://github.com/zulip/zulip-mobile/pulls?utf8=%E2%9C%93&q=author%3Akunall17%20)
* [More about Zulip](https://zulipchat.com/)

### Contribution

###### _(List of main features worked on)_

* [Push notifications for android & ios](#push-notifications-for-android--ios)
* [Implemented prettier (code formatting)](#implemented-prettier-code-formatting))
* [Hooked up detox E2E & the prettier formatting check](#hooked-up-detox-e2e-&-the-prettier-formatting-check)
* [Markdown parser (converts markdown to html for messages)](#markdown-parser-(converts-markdown-to-html-for-messages))
* [Several changes in the settings screen](#several-changes-in-the-settings-screen)
* [Use parser to locally echo the message sent](#use-parser-to-locally-echo-the-message-sent)
* [Implemented the outbox functionallity](#implemented-the-outbox-functionallity)
* [Message auto saved as drafts](#implemented-the-outbox-functionallity)
* [Full screen markdown editor](#implemented-the-outbox-functionallity)
* [Pleothera of other fixes](#pleothera-of-other-fixes)
* [Message auto saved as drafts](#message-auto-saved-as-drafts)
* [Full screen markdown editor](#full-screen-markdown-editor)


###### _(Details on the above listed)_


##### Push notifications for android & ios



##### End to end integration test's using appium & detox
##### Rework on the compose box design
##### Menu for the long press of message
##### Editing message made possible
##### Implemented prettier (code formatting)
##### Hooked up detox E2E & the prettier formatting check
##### Markdown parser (converts markdown to html for messages)
##### Several changes in the settings screen
##### Use parser to locally echo the message sent
##### Implemented the outbox functionallity
##### Pleothera of other fixes
##### Message auto saved as drafts
##### Full screen markdown editor



[Fix: Muted topics were being displayed in homeView](https://github.com/zulip/zulip-mobile/pull/410)  
[Fix: NoSuchMethodError for builder.addAction](https://github.com/zulip/zulip-mobile/pull/1088)  
[Use result of post request for sending message](https://github.com/zulip/zulip-mobile/pull/1079)  
[Fix eventQueueId in appReducers](https://github.com/zulip/zulip-mobile/pull/1076)  
[[WIP] Fix flow, jest unit test errors](https://github.com/zulip/zulip-mobile/pull/1068)  
[Fix chatReducers EVENT_NEW_MESSAGE incorrect implementation](https://github.com/zulip/zulip-mobile/pull/1066)  
[Added log statment and enabled background modes for ios notifications](https://github.com/zulip/zulip-mobile/pull/1054)  
[Fix for unauthorized access and push notification](https://github.com/zulip/zulip-mobile/pull/1051)  
[Fix outbox bugs](https://github.com/zulip/zulip-mobile/pull/1041)  
[Implement action sheet for outbox messages](https://github.com/zulip/zulip-mobile/pull/1022)  
[Implement drafts screen](https://github.com/zulip/zulip-mobile/pull/1019)  
[Use outbox messages to render messages to the chat screen](https://github.com/zulip/zulip-mobile/pull/1014)  
[Fix re-rendering of AppContainer due to outbox](https://github.com/zulip/zulip-mobile/pull/1009)  
[Fix: Upgrade expo actionsheet due to BackAndroid being deprecated](https://github.com/zulip/zulip-mobile/pull/1005)  
[Fix android GCM push notifications](https://github.com/zulip/zulip-mobile/pull/1000)  
[Fix react-native-fetch-blob package crash](https://github.com/zulip/zulip-mobile/pull/999)  
[Implement reducers and actions for outbox and use it in ComposeBox](https://github.com/zulip/zulip-mobile/pull/977)  
[Fix master branch flow errors](https://github.com/zulip/zulip-mobile/pull/976)  
[Fetch realm_filters and its event updates](https://github.com/zulip/zulip-mobile/pull/956)  
[Implement markdown parser to convert markdown to html](https://github.com/zulip/zulip-mobile/pull/949)  
[Display topic input only in stream narrow](https://github.com/zulip/zulip-mobile/pull/945)  
[Separate language to another screen in settings screen](https://github.com/zulip/zulip-mobile/pull/944)  
[Fixes #934: Play zulip.mp3 on android push notification](https://github.com/zulip/zulip-mobile/pull/943)  
[Fix release build through command line errors](https://github.com/zulip/zulip-mobile/pull/940)  
[Fix unread selectors and fix eslint error](https://github.com/zulip/zulip-mobile/pull/928)  
[Added detox smoke test's in the travis CI](https://github.com/zulip/zulip-mobile/pull/915)  
[Use prettier-check to check if all files are formatted with prettier](https://github.com/zulip/zulip-mobile/pull/910)  
[Fix: Downgrade photoview dependency to 1.2.0](https://github.com/zulip/zulip-mobile/pull/899)  
[Handle back pressed in android](https://github.com/zulip/zulip-mobile/pull/898)  
[Full screen markdown editor](https://github.com/zulip/zulip-mobile/pull/882)  
[Fix: navigation to dev auth screen](https://github.com/zulip/zulip-mobile/pull/873)  
[Renable prettier and fix all issues related to it](https://github.com/zulip/zulip-mobile/pull/859)  
[Implement prettier for the project](https://github.com/zulip/zulip-mobile/pull/850)  
[Use translated strings in message action sheet](https://github.com/zulip/zulip-mobile/pull/829)  
[Add online notification switch to settings](https://github.com/zulip/zulip-mobile/pull/828)  
[Replace appium with detox](https://github.com/zulip/zulip-mobile/pull/825)  
[Don't show message's count if only 1 message in the android notifications](https://github.com/zulip/zulip-mobile/pull/802)  
[Show action sheet on long press of header](https://github.com/zulip/zulip-mobile/pull/801)  
[Use big view styles for 1 conversation](https://github.com/zulip/zulip-mobile/pull/755)  
[Fetch updates for notification and display settings](https://github.com/zulip/zulip-mobile/pull/754)  
[Fixes #683: Split users into users and presence](https://github.com/zulip/zulip-mobile/pull/750)  
[Add a setting for enabling offline push notifications](https://github.com/zulip/zulip-mobile/pull/748)  
[Fix: Receive twentyFourHourTime from the server on intital fetch](https://github.com/zulip/zulip-mobile/pull/747)  
[Implementation of ios push notifications](https://github.com/zulip/zulip-mobile/pull/746)  
[Grouped notifications into one and show the notifications as a list](https://github.com/zulip/zulip-mobile/pull/734)  
[Hide mode changer as there is only one compose option: compose text](https://github.com/zulip/zulip-mobile/pull/694)  
[Hide other icons in the ComposeOptions](https://github.com/zulip/zulip-mobile/pull/689)  
[New compose box design for private messages](https://github.com/zulip/zulip-mobile/pull/678)  
[Initial implementation of android GCM push notifications](https://github.com/zulip/zulip-mobile/pull/637)  
[Fixes #633: Remove ActionSheetProvider from root in the chat.js](https://github.com/zulip/zulip-mobile/pull/634)  
[Fix: Renamed mute topic & streams](https://github.com/zulip/zulip-mobile/pull/631)  
[Add integration testing using appium for the iOS](https://github.com/zulip/zulip-mobile/pull/602)  
[Add API calls for muting/unmuting stream/topic](https://github.com/zulip/zulip-mobile/pull/574)  
[Added reducers for receiving updates on subscriptions and muted topics](https://github.com/zulip/zulip-mobile/pull/569)  
[New compose box design](https://github.com/zulip/zulip-mobile/pull/561)  
[Implemented Muting/Unmuting of streams and topics](https://github.com/zulip/zulip-mobile/pull/415)  
[Implemented editing message](https://github.com/zulip/zulip-mobile/pull/402)
