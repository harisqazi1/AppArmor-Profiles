# AppArmor Profiles

These are AppArmor profiles for some of the applications I use. These are meant to be standalone. There is no `#include xyz` as that makes things get complicated in the long run, since you not only have to manage one file, but the includes as well. My profiles **will not** work for you right off the bat. You will have to fine tune it based on your system. As such, my recommendation would be to jump between `aa-complain application_name` and `aa-logprof` to fine tune your profile.

These profiles are really granular and do not use variables. I am a beginner at this, so the profiles will get better as time goes on. In the mean time, check out the following projects by people who have a better understanding of what they are doing:
- [GitHub - roddhjav/apparmor.d: Full set of AppArmor profiles (~ 1500 profiles)](https://github.com/roddhjav/apparmor.d)
- [GitHub - krathalan/apparmor-profiles: Krathalan&#39;s AppArmor profiles for Arch Linux](https://github.com/krathalan/apparmor-profiles)
## Summary of Profiles
- Firefox
  - Blocks access to /root
  - Allows for audio
  - Blocks access to all user files other than ~Downloads
- more coming soon...
