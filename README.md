zoukyle.github.io
=================
0. windows key + R, then cmd
1. cd C:\Python27\Scripts
2.  .\hyde.exe -s C:\Users\liangzou\Documents\photography_site\lzp-site-hyde gen
3.  .\hyde.exe -s C:\Users\liangzou\Documents\photography_site\lzp-site-hyde serve

Make sure all the changes are good.

4. Change mode: prod in site.yaml
5. .\hyde.exe -s C:\Users\liangzou\Documents\photography_site\lzp-site-hyde gen
6. Change mode: dev in site.yaml

7. Start the *github* application
8. Commit the changes to zoukyle.github.io and lzp-site-hyde

How to upload images to Google App Engine
=========================================
The static image files are served on the Google App Engine because it's free.
The steps to upload new images:
1. Add images to C:\Users\liangzou\Documents\bookmarks\static\images\lzp
2. cd C:\Users\liangzou\Documents\bookmarks
3. dev_appserver.py app.yaml to make sure the local instance works.
4. gcloud app deploy to deploy to the cloud.
