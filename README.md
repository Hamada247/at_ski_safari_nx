# ski_safari_nx (work in progress)

Port code for running the 32-bit Android version of Ski Safari: Adventure Time
on a Nintendo Switch with the android32 runtime.

**Do not put the APK or any game files in this repository.**

## Step 0 - check the toolchain (no game code yet)
1. Open the **Actions** tab of this repository.
2. Choose **Toolchain check** and press **Run workflow**.
3. Wait. The first run builds Mesa and is slow. Later runs reuse a cache.
4. Green = the toolchain works. Red = open the failed step and copy the last
   30 lines of its log.
