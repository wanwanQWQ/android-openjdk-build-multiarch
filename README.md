Based on http://openjdk.java.net/projects/mobile/android.html

Download Android NDK r14 from https://developer.android.com/ndk/downloads/older_releases.html and place it in this directory

(Can't automatically download because of EULA)

## Building

### Environment variables
<table>
      <thead>
        <tr>
          <th></th>
          <th align="center" colspan="7">Architectures</th>
        </tr>
        <tr>
          <th>Env var</th>
          <th align="center">TARGET</th>
          <th align="center">TARGET_JDK</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>armv8/aarch64</td>
          <td align="center">aarch64-linux-android</td>
          <td align="center">aarch64</td>
        </tr>
        <tr>
          <td>armv7/aarch32</td>
          <td align="center">arm-linux-androideabi</td>
          <td align="center">arm</td>
        </tr>
        <tr>
          <td>x86/i686</td>
          <td align="center">i686-linux-android</td>
          <td align="center">x86</td>
        </tr>
        <tr>
          <td>x86_64/amd64</td>
          <td align="center">x86_64-linux-android</td>
          <td align="center">x86_64</td>
        </tr>
      </tbody>
	</table>

### Run in this directory:
```
bash ci_build_global.sh
```
