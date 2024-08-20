# Gathr Usage Guide [v1.2.0]

1. [Mobile App](#mobile-app)
  1. [Creating Posts](#creating-posts)
  2. [Who Can See My Posts](#who-can-see-my-posts)
  3. [Leaderboard](#leaderboard)
  4. [Bring Users from Instagram to RSVP on Gathr by Posting Directly to Your Story](#bring-users-from-instagram-to-rsvp-on-gathr-by-posting-directly-to-your-story)
2. [Admin Dashboard](#admin-dashbaord)
  1. [Attendance and RSVPs](#attendance-and-rsvps)

## Mobile App

### Creating Posts

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

### Who Can See My Posts

- As you'd expect, users who follow you will receive a push notification about your post. The same applies to users who follow the community you posted in.
- However, the main Gathr feed shows all posts across the platform, sorted by a chosen metric:
  - **Top [Today, This Month, All Time]:** Sorted by likes, filtered by time range.
  - **New:** Sorted by time created.
  - **Hot:** A special metric that prioritizes posts that are both new and have more likes.
- More posts → more engagement → more follows → more users notified → more engagement, etc.
- We're working tirelessly to bring new users to the platform and make posting here worth your while!

### Leaderboard

- The leaderboard is intended to boost engagement by increasing exposure to clubs with more contributions on the app. All organizations are assigned a variable amount of points for the following actions:
  - Receiving a like, comment, or follow
  - Creating a post
- These points reset on the first day of every month at midnight UTC. We plan on using this feature to create incentives for clubs with leaderboard rankings each month!

### Bring Users from Instagram to RSVP on Gathr by Posting Directly to Your Story

1. On your post, click on the **Share Button** in the bottom right corner. Click on **"Share to Instagram Story."**
2. Instagram will open up with your post pasted in automatically. Your post has been copied to your clipboard, so add a link to it:
   - Click on the **Sticker Icon** in the top right corner and select **Link.**
   - Long-press and click **Paste,** then click **Done.**
   - Drag the link below your post into the placeholder area. When users click on this, they'll be redirected automatically to your post if they have Gathr installed, or to the App Store otherwise.
   - *Note: We wish we could automate the link part, but Instagram doesn't allow it.*
3. *Quick tip: You can also share posts, communities, and profiles via a link.*

## Admin Dashboard

The admin dashboard can be found on our website, [getgathr.app](https://getgathr.app), by clicking on **"Dashboard"** in the top right corner. Here is a [direct link](https://getgathr.app/dashboard).

### Attendance and RSVPs

- Go to **Attendance and RSVPs** in the left sidebar and select your event to see who has RSVP'd. This data can be exported as a CSV file using the **Export** button.
- **Copy Check-In Link** and **Download Check-In QR Code:** These features create a link which allow users to sign into your event. The QR code generated by the latter points to the same link as the former—it is simply generated for your convenience. You can use the raw link if you want to use another QR-generating service with your preferred style. Note that while Gathr is not available for Android, the QR and link will still work for Android users—they will simply be redirected to a web-based check-in.
- **Open QR Check-In:** Use this to allow people to sign in to your event. QR check-in can be disabled and enabled anytime. Note that check-in for events is disabled by default, and must be enabled from the dashboard in order for users to check in via QR code.
- **Manual Attendance Upload:** This is feature can be used in cases where you may want to manually add users to the attendance list. For example, maybe someone showed up to an event but their phone died before they could sign in, or maybe you want to store attendance data previously taken on a Google Form. Create a Google Sheet with a single column titled "email" and add the emails of people you want to manually check in. Alternatively, you can export your Google Form as a CSV and upload the same.
- **Filters:** You can currently filter between *All*, *Only RSVP-ers*, and *Only Attendees*. This will filter the attendance table, and the data exported via the **Export** button will reflect the same.


#### Releases
[1.2.0](https://github.com/gathr-app/gathr-features/tree/release_1.2.0)
[1.1.0](https://github.com/gathr-app/gathr-features/tree/release_1.1.0)
[1.0.2](https://github.com/gathr-app/gathr-features/tree/release_1.0.2)
