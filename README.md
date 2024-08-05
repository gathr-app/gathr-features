# Gathr Usage Guide

[View other versions](https://github.com/gathr-app/gathr-features)

## Creating Posts

- You can create posts not only to promote events but to make general announcements as well.
- All posts are associated with a community. This principle is based on the idea that people will subscribe to the community related to the content they're interested in.
- **Steps to Create a Post:**
  1. Click on the **Plus Button** in the bottom right corner.
  2. Select a community to post in. We recommend using either `parties`, `socials`, or `gbm` for events, and `general` for all other communication.
     - If you're already viewing a community from the sidebar, you won't be prompted to select the community again.
  3. Add some descriptive text. Optionally, add an image.
  4. **Customize your post:** You can specify the following details:
     - **RSVP:** This feature is meant for any event. If enabled, a button will appear beneath your post to allow users to RSVP. You can track this in the dashboard (explained later). Additionally, you can set an RSVP limit beyond which nobody can RSVP. This is a good feature for events with a maximum capacity.
     - **Date:** If enabled, a button will appear below your post allowing users to add the event to their device's calendar. They will be notified about the event 15 minutes prior to the start time. You will need to specify an Event Title to determine what the event will be stored as on the user's calendar.
     - **Location:** If specified, conveniently displays an event location below your post.
  5. Click **Post!**
  6. *Optional: Post directly to your Instagram story (explained later).*

## Who Can See My Posts?

- As you'd expect, users who follow you will receive a push notification about your post. The same applies to users who follow the community you posted in.
- However, the main Gathr feed shows all posts across the platform, sorted by a chosen metric:
  - **Top [Today, This Month, All Time]:** Sorted by likes, filtered by time range.
  - **New:** Sorted by time created.
  - **Hot:** A special metric that prioritizes posts that are both new and have more likes.
- More posts → more engagement → more follows → more users notified → more engagement, etc.
- We're working tirelessly to bring new users to the platform and make posting here worth your while!

## Bring Users from Instagram to RSVP on Gathr by Posting Directly to Your Story

1. On your post, click on the **Share Button** in the bottom right corner. Click on **"Share to Instagram Story."**
2. Instagram will open up with your post pasted in automatically. Your post has been copied to your clipboard, so add a link to it:
   - Click on the **Sticker Icon** in the top right corner and select **Link.**
   - Long-press and click **Paste,** then click **Done.**
   - Drag the link below your post into the placeholder area. When users click on this, they'll be redirected automatically to your post if they have Gathr installed, or to the App Store otherwise.
   - *Note: We wish we could automate the link part, but Instagram doesn't allow it.*
3. *Quick tip: You can also share posts, communities, and profiles via a link.*

## Check Your RSVPs

- The admin dashboard can be found on our website, [getgathr.app](https://getgathr.app), by clicking on **"Dashboard"** in the top right corner. Here is a [direct link](https://getgathr.app/dashboard).
- Go to **Attendance and RSVPs** in the left sidebar and select your event to see who has RSVP'd. This data can be exported as a CSV file using the **Export** button.

## Cross-Reference Attendance

- This feature can be used to compare RSVPs versus attendance and store this data for compatibility with future member management features. It is currently among our top priorities for updating, as we feel the current implementation is still somewhat unwieldy. This will be replaced with QR code-based attendance soon.
  1. Under **Attendance and RSVPs** as before, click on **"Cross-reference attendance."**
  2. In another tab, go to the Google Form you used to take attendance for your event.
     - Click on **Responses → More Options [⋮] → Download responses (.csv).**
  3. Unzip the CSV file and upload it. Your attendance data will be saved and used for future member management features.
     - *Note: In order for this feature to work, the Google Form you used to take attendance MUST have a text input called "email."*
