# TCMe Privacy Policy

Effective date: [Insert Date]

TCMe is a close-friends social app. This Privacy Policy explains what information TCMe collects, why it is used, who can see it, and what happens when you delete your account.

Contact: [tcme.support@gmail.com]

## Information We Collect

### Account Information

TCMe uses Supabase Auth for account creation, login, and password reset. We collect your email address and authentication information needed to maintain your account. Your password is handled by Supabase Auth and is not visible to other TCMe users.

### Profile Information

Your profile may include your nickname, profile status, status symbol, card style, Bluetooth pairing token, and optional profile photo. This information is used to show your profile card, help friends recognize you, and support friend pairing.

Your profile information is visible to people in your TCMe network, including friends, chat participants, and group chat members.

### Posts, Photos, Comments, and Likes

TCMe lets you create text posts, photo posts, comments, and likes. Posts and comments are only intended to be visible to your close network. Users cannot browse posts or comments from strangers outside their network.

Uploaded profile photos are stored in Supabase Storage in the `avatars` bucket. Uploaded post images are stored in Supabase Storage in the `post-images` bucket.

### Messages and Group Chats

TCMe stores direct chat messages between friends and group chat messages between group members. Direct messages are visible to the sender and recipient. Group messages are visible to members of the group.

### Friend Requests and Friendships

TCMe uses Bluetooth-based pairing to add friends. Friend requests and friendship records are stored to create and maintain your network. Friend connections expire silently after one year and one week.

### Reports

You can report users, posts, or comments. Reports may include the reporter, reported user, reason, optional details, status, and related post or comment reference. Reports are reviewed manually and are visible to TCMe administrators for safety and moderation purposes.

### Notifications

TCMe currently uses in-app notifications for app activity such as likes and comments.

TCMe is planned to support push notifications before release through Apple Push Notification service (APNs). Push notifications may be used for new messages, friend requests, likes, comments, and friendship events. To provide this feature, TCMe may store a device push token supplied by Apple and associate it with your account. Push notifications may include limited event information, such as who sent a message, liked a post, commented, or sent a friend request.

You can disable push notifications through your device settings.

## Device Permissions

TCMe uses Bluetooth to help you find nearby friends who are also pairing. TCMe does not send precise location data to the backend.

TCMe uses the system photo picker when you choose a profile photo or photo post. You choose which image to upload.

TCMe does not currently use camera capture, location services, address book contacts, analytics SDKs, advertising SDKs, or tracking SDKs.

## Third-Party Services

TCMe uses Supabase for authentication, database, storage, and app data. Planned push notifications will use Apple Push Notification service.

We do not use third-party advertising or tracking services.

## Account Deletion

You can delete your account from inside TCMe. Before deletion, TCMe requires password confirmation.

When deletion is successful, TCMe deletes or removes:

- Your profile row
- Friend requests involving you
- Friendships involving you
- Direct messages involving you
- Comments by you and comments on your posts
- Likes by you and likes on your posts
- Notifications involving you
- Your posts
- Your profile photo file from Supabase Storage
- Your post image files from Supabase Storage
- Your local app cache, including cached profile data, avatar data, posts, chats, friends, notifications, muted chat IDs, and image cache responses

For group chats, TCMe removes you from group memberships and deletes messages you sent. TCMe does not delete a group for everyone just because you created it.

Reports are not deleted immediately because they may be needed for safety and moderation records. When your account is deleted, report user identifiers are anonymized where applicable.

If push notifications are implemented, TCMe will also delete push tokens associated with your account during account deletion.

After account deletion, TCMe signs you out.

## Data We Do Not Collect

TCMe does not collect financial information, health data, address book contacts, browsing history, search history, advertising identifiers, analytics tracking data, or precise location data.

## Changes to This Policy

We may update this Privacy Policy as TCMe changes. If we make material changes, we will update the effective date and, where appropriate, notify users in the app.

