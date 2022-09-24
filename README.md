# Owncast on Fly.io

## Getting started
1. Launch the app with `fly launch`
2. Create a volume with `fly volumes create <volume_name>` and update `owncast_data` accordingly
3. Deploy the app with `fly deploy` if not deployed yet
4. Access the admin panel at `https://<app_name>.fly.dev/admin` with the username `admin` and password `abc123`. Be sure to (re)set your stream key to reset the admin password!
5. Stream to your Owncast instance with `rtmp://<app_name>.fly.dev:1935/live` (unencrypted) or `rtmps://<app_name>.fly.dev:1936/live` to use encrypted RTMPS!
