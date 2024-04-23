# WhatsApp API Endpoints

This repository contains documentation for the endpoints of a WhatsApp API, which provides various functionalities for interacting with WhatsApp services. Below is a list of available endpoints along with their descriptions and request methods.

## Session

- **POST /session/init**: Initializes a new user session.
- **GET /session/all**: Retrieves all users stored in the database.
- **POST /session/connect**: Connects to WhatsApp servers.
- **POST /session/pair**: Connects to WhatsApp with the pair code.
- **POST /session/disconnect**: Disconnects from WhatsApp servers.
- **POST /session/logout**: Logs out from WhatsApp.
- **GET /session/status**: Retrieves connection and session status.
- **GET /session/qr**: Retrieves QR code for scanning.

## Webhook

- **GET /webhook**: Shows webhook.
- **POST /webhook**: Sets webhook.

## User

- **POST /user/info**: Retrieves information about users on WhatsApp.
- **POST /user/check**: Checks if a user has WhatsApp.
- **GET /user/avatar**: Retrieves profile picture information.
- **GET /user/privacy**: Retrieves user privacy setting.
- **GET /user/contacts**: Retrieves all contacts for the account.
- **POST /user/block**: Blocks a user.
- **POST /user/profile**: Updates user profile.
- **POST /user/unblock**: Unblocks a user.
- **GET /user/blocklist**: Retrieves block contact list.
- **POST /user/name**: Updates user profile name.
- **POST /user/presence**: Updates user presence.

## Chat

- **POST /chat/pin**: Pins a chat.
- **POST /chat/unpin**: Unpins a chat.
- **POST /chat/mute**: Mutes a chat.
- **POST /chat/archive**: Archives a chat.

## Message

- **POST /message/markread**: Marks a message as read.
- **POST /message/status**: Retrieves message status with its MessageID.
- **POST /message/edit**: Edits a message with its MessageID.
- **POST /message/react**: Reacts to a message.
- **POST /message/downloadimage**: Downloads image from message.
- **POST /message/delete**: Deletes a message for everyone in a chat.
- **POST /message/presence**: Sets chat presence.

## Label

- **POST /label/chat**: Adds a label to a chat.
- **POST /unlabel/chat**: Unlabels a label from a chat.
- **POST /label/message**: Adds a label to a message.
- **POST /unlabel/message**: Unlabels a label from a message.
- **POST /label/edit**: Edits a label.

## Send

- **POST /send/text**: Sends a text message.
- **POST /send/poll**: Sends a poll message.
- **POST /send/image**: Sends an image/picture message.
- **POST /send/audio**: Sends an audio message.
- **POST /send/document**: Sends a document message.
- **POST /send/template**: Sends a template message.
- **POST /send/buttons**: Sends one or multiple buttons.
- **POST /send/mediabutton**: Sends one or multiple media buttons (with image).
- **POST /send/mediaurl**: Sends media using a direct URL.
- **POST /send/video**: Sends a video message.
- **POST /send/sticker**: Sends a sticker message.
- **POST /send/location**: Sends a location message.
- **POST /send/contact**: Sends a contact message.
- **POST /send/list**: Sends a list message.

## Group

- **POST /group/create**: Creates a group.
- **POST /group/join**: Joins a group.
- **POST /group/update**: Updates group members.
- **GET /group/list**: Lists subscribed groups.
- **GET /group/myall**: Retrieves all groups in which you're an admin.
- **POST /group/leave**: Leaves a group.
- **POST /group/invitelink**: Retrieves a group invite link.
- **POST /group/info**: Retrieves group information.
- **POST /group/name**: Changes group name.
- **POST /group/photo**: Changes group photo.

## Newsletter

- **POST /newsletter/create**: Creates a newsletter.
- **GET /newsletter/list**: Lists all newsletters.
- **POST /newsletter/info**: Retrieves newsletter info.
- **POST /newsletter/link**: Retrieves newsletter info with a link.
- **POST /newsletter/subscribe**: Subscribes to a newsletter.
- **POST /newsletter/messages**: Retrieves newsletter messages.

## Community

- **POST /community/create**: Creates a community.
- **POST /community/add**: Adds a group to a community.
- **POST /community/remove**: Removes a group from a community.

## Business

- **POST /business/get/profile**: Retrieves business profile.
- **GET /business/get/categories**: Retrieves business categories.
- **POST /business/update/desc**: Updates business description.
- **POST /business/update/address**: Updates business address.
- **POST /business/update/email**: Updates business email.
- **POST /business/catalog/list**: Retrieves full catalog.
- **POST /business/catalog/create**: Creates a product for the catalog.
- **POST /business/catalog/edit**: Edits a product from the catalog.
- **POST /business/catalog/info**: Retrieves a product from the catalog.
- **POST /business/catalog/delete**: Deletes a product from the catalog.
- **POST /business/catalog/show**: Changes product visibility.
- **POST /business/catalog/hide**: Changes product visibility.

## Call

- **GET /call/ok**: Checks if the server is up.
- **POST /call/license**: Checks license expiry.
- **GET /call/update**: Checks or updates to the latest version.

## Test

- **POST /test**: Endpoint for testing.

