# noto-cjk-fix

A fix for Noto Sans CJK, which doesn't open properly in FontForge.


## Steps

1. Head to <<https://github.com/googlefonts/noto-cjk>>

2. Inspect the history of `LICENSE`:
   <<https://github.com/googlefonts/noto-cjk/commits/main/LICENSE>>

3. Confirm that commit `5375192` is where the license changes
   from Apache 2.0 to SIL OFL 1.1:
   <<https://github.com/googlefonts/noto-cjk/commit/5375192>>

4. The parent commit, `2663656`, is therefore the last version
   where the license is still Apache 2.0:
   <<https://github.com/googlefonts/noto-cjk/commit/2663656>>

5. Browse the repository at `2663656`:
   <<https://github.com/googlefonts/noto-cjk/tree/2663656>>

6. Confirm that the license is Apache 2.0:
   <<https://github.com/googlefonts/noto-cjk/blob/2663656/LICENSE>>

7. Obtain `NotoSansCJKtc-Regular.otf` as of `2663656`:
   <<https://github.com/googlefonts/noto-cjk/blob/2663656/NotoSansCJKtc-Regular.otf>>

8. Check SHA-256:
   `b089537a68a5b7ce5fe4fe6cd2667a489aa1016d23d14115bf032899e420b635`

9. Open `NotoSansCJKtc-Regular.otf` with trial version of FontLab 7

10. Export font to `NotoSansCJKtc-Regular-FIXED.ttf`
