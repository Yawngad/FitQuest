# Build FitQuest APK from your phone with GitHub Actions

This is a cloud-build workflow. GitHub will compile the Android project and let you download the APK as a workflow artifact.


## Steps
1. Create/sign in to GitHub.
2. Create a new repository (public or private) named `FitQuestAndroid`.
3. Upload the contents of this `FitQuestAndroid` folder to the repository root (make sure `.github/workflows/build-apk.yml` is included).
4. Open the repository's **Actions** tab.
5. Select **Build FitQuest APK** from the workflows list.
6. Press **Run workflow** and confirm.
7. Wait for the run to finish successfully, open that run, and download the `FitQuest-debug-apk` artifact.
8. Extract the downloaded ZIP artifact to get the `.apk`, then install it on your Android phone. If prompted, allow your file manager/browser to install unknown apps.


If the build fails, open the failed run's log and share it so it can be diagnosed.
