# gcal 4.1 (maintained fork)

> [!TIP]
> Install on macOS with Homebrew via the [erikdw/gcal tap](https://github.com/erikdw/homebrew-gcal):
>
> ```
> brew install erikdw/gcal/gcal
> ```

This is a fork of [GNU Gcal 4.1](https://www.gnu.org/software/gcal/), the GNU
Gregorian calendar program, which is no longer maintained upstream (last
release: 2015). This fork exists to keep it building and current:

- Fixed the build on modern macOS (`sys/ioctl.h` / `ioctl()` under recent Clang)
- Added Juneteenth as a US federal holiday (observed from 2021 onward)

See the original [README](README) for the full description of Gcal itself.
