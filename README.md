# LiveFaceSwap AI Scoop bucket

Personal [Scoop](https://scoop.sh) bucket maintained by [LiveFaceSwap AI](https://livefaceswap.ai).

## Apps

| App | Description |
| --- | --- |
| `find-camera-users` | Find Camera Users: a free, read-only Windows script that shows which program Windows reports as using your webcam. |

## Install

```powershell
scoop bucket add livefaceswap https://github.com/LiveFaceSwapAI/scoop-bucket
scoop install livefaceswap/find-camera-users
find-camera-users
```

## About Find Camera Users

If an app says "camera is in use" or your webcam shows a black screen, Find Camera Users lists the program that Windows
currently reports as using the camera (with process ID and window title), or the last app that used it. It is a
troubleshooting helper from LiveFaceSwap AI, for example before starting a LiveFaceSwap AI session.

- Read-only: it only reads the current user's Windows camera usage records and the matching processes.
- No camera capture, no network access, no data collection or upload.
- Does not change any settings and does not end any process.
- For browsers, Windows reports only the browser, not the exact tab.

Direct download: https://r2.livefaceswap.ai/downloads/camera-checker/2026-11-16-a9caecf696/Find-Camera-Users.bat
(SHA-256 `a9caecf6964fddc0f064fe031ecbdb3b90d93108ff53c559dd1508ec2bd09a1d`)
