### TailwindCSS styling issue

8/3/2026

- I didn't quit, I found the bug - I had upgraded to V4 but the compiled styles are still V3 and I can't re-compile. I got further today than I have in the last 6 months.

9/3/2026

- After some investigation the TailwindCSS upgrade had some changes in the imports which were causing an error in compilation and needed reverting to V3. There was also a V4 reference still being used in the styles which needed removing.