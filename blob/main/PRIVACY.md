# FrameAI — Privacy Policy

**Effective date:** 12 July 2026
**Applies to:** the FrameAI app for iOS and Android.

## The short version

FrameAI does not collect your data. There is no account, no analytics, no advertising, no
tracking, and no server that receives your photos. All image processing happens on your
device, and the app works with no network connection at all.

## Your photos

When you choose a photo, FrameAI reads it from your device's photo library and stylizes it
locally, using machine-learning models that are stored on the device itself.

**Your photos never leave your device.** They are not uploaded, not backed up by us, not
sent to any server, and not seen by us or by anyone else. This is not a policy promise we
ask you to take on trust — there is no backend to send them to. You can verify it by
putting the device in airplane mode: every stylization feature still works.

The result is saved or shared only when you explicitly choose to do so, and it goes wherever
you send it (your photo library, another app), never to us.

We request photo-library access solely to let you pick a source image and to save your
finished artwork. We do not scan, index, or read anything else in your library.

## What we collect

**Nothing.** We operate no servers, hold no accounts, and store no personal data of any kind.

FrameAI contains no analytics SDK, no crash-reporting SDK, no advertising SDK, and no
third-party trackers. We do not create a user profile, we do not assign you an identifier,
and we have nothing to sell, share, or lose in a breach.

## The one time FrameAI touches the network

FrameAI's built-in styles work entirely offline. The app makes an outbound connection in
exactly one situation: when you open the **Model packs** screen or download an optional
style pack.

In that case, the app fetches a manifest file and pack archives from **GitHub**
(`github.com/argiad/frameai-packs`). We want to be precise about what this means, because
"we collect nothing" should not be used to paper over it:

- We receive nothing. The request goes to GitHub, not to us.
- As with any request to any website, **GitHub's servers will see your device's IP address**
  and standard connection metadata. That data is handled by GitHub under
  [GitHub's Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-privacy-statement),
  not by us, and we have no access to it.
- No photo, no stylized image, and no information about what you have made is included in
  these requests. We cannot tell what you have created, and neither can GitHub.
- If you never open the Model packs screen, FrameAI makes no network requests at all.

Downloaded packs are verified against a SHA-256 checksum before installation and stored
locally on your device. You can delete any downloaded pack from within the app.

## Third parties

We share your data with no one, because we hold none.

FrameAI is distributed through the Apple App Store and Google Play. Those platforms may
collect their own data about downloads, crashes, and purchases under their own privacy
policies, which we do not control and from which we receive no personal information about
you. See Apple's and Google's privacy policies for details.

## Children

FrameAI is safe for all ages and collects no data from anyone, children included. Because we
collect nothing, we cannot knowingly or unknowingly collect a child's personal information.

## Your rights (GDPR, CCPA, and similar laws)

Laws such as the GDPR and the CCPA give you rights to access, correct, delete, or port the
personal data a company holds about you, and to opt out of its sale.

We hold no personal data about you, so there is nothing to access, correct, delete, port, or
opt out of. Any data FrameAI creates — your photos, your custom styles, your downloaded
packs — lives only on your device and is under your control. Deleting the app deletes it.

We have never sold or shared personal data, and we have no mechanism to do so.

## Changes to this policy

If FrameAI ever gains a feature that changes any of the above, this document will be updated
before that feature ships, and the effective date at the top will change. The full revision
history of this file is public in the repository, so you can see exactly what changed and
when.

## Contact

Questions about this policy: **support@example.com** *(← replace with your real address)*

You can also open an issue at
[github.com/argiad/frameai-packs/issues](https://github.com/argiad/frameai-packs/issues).
