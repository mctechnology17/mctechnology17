[![MC Technology](src/mctechnology_extendido.GIF)](https://www.youtube.com/c/mctechnology17)

<h1 align="center">
  Marcos - MC Technology
  &nbsp;
  <a href="https://youtube.com/@mctechnology17" title="YouTube" target="_blank" rel="noopener">
    <img src="./src/youtube.png" width="30" alt="YouTube">
  </a>
  <a href="https://www.reddit.com/user/mctechnology17" title="Reddit" target="_blank" rel="noopener">
    <img src="./src/reddit.png" width="30" alt="Reddit">
  </a>
  <a href="https://www.linkedin.com/in/marcos-chow-castro-56a300255/" title="LinkedIn" target="_blank" rel="noopener">
    <img src="./src/linkedin.png" width="30" alt="LinkedIn">
  </a>
</h1>

<h3 align="center"><img src="./src/cabeza.GIF" width="30" height="30" alt="logo"> Projects</h3>

- 🔭 [zmk-nice-oled] – Vertical widgets for OLED & MiP-LCD screens using ZMK (split & non-split)
- 🖥️ [zmk-dongle-display-view] – Horizontal widgets for OLED & MiP-LCD screens, ready-made widgets
- 🧩 [zmk-oled-adapter] – Adapter for OLEDs in ZMK without modifying keyboard shields
- 🧰 [zmk-config] – Quickly and easily configure your wireless Corne / Sofle / Lily58 keyboard with ZMK.
- ⚙️ [qmk-config] – Quickly and easily configure your keyboard using QMK
- 👤 [qmk_userspace] – QMK USER SPACE for keyboards
- 🛠️ [vimtools] – Swiss-army knife for Vim (features & settings to speed you up)
- 🌲 [gm] – Cross-platform Git manager with a friendly UI
- 🧾 [vim-better-header] – Automated, clean file headers
- ▶️ [vim-executor] – Multi-language code executor

> Tipp: Click on the project names to jump directly to the repos.

---

<h3 align="center"><img src="./src/0101.GIF" width="25px" height="25px"> Languages and Tools</h3>

Execute `make run` in your thoughts to see the exit of the code ;)

```c
/* =======================================================
 *                Languages & Tools (README)
 * FileName: readme.c
 * Run: /usr/bin/clang -O2 readme.c -o readme && ./readme
 * =======================================================
 */

#include <stdio.h>

#define COUNT(a) (sizeof(a) / sizeof((a)[0]))

static const char* OS[]      = { "Linux", "macOS", "Windows"};
static const char* LANG[]    = { "C", "Python", "R", "Java" };
static const char* EDITOR[]  = { "Vim" };
static const char* SHELLS[]  = { "Bash" };
static const char* TOOLS[]   = { "Docker", "Git" };

static void show(const char* title, const char* v[], size_t n) {
    printf("• %-7s: ", title);
    for (size_t i = 0; i < n; ++i) printf("%s%s", v[i], (i + 1 < n ? ", " : "\n"));
}

int main(void) {
    puts("{");
    show("OS",     OS,     COUNT(OS));
    show("Code",   LANG,   COUNT(LANG));
    show("Editor", EDITOR, COUNT(EDITOR));
    show("Shell",  SHELLS, COUNT(SHELLS));
    show("Tools",  TOOLS,  COUNT(TOOLS));
    puts("}");
    return 0;
}
// vim: set fdm=marker:
```

---

<h3 align="left"><img src="./src/youtube.gif" width="70px" height="25px"> latest Videos</h3>

<!-- YOUTUBE:START -->
- [corne keyboard animaciones con QMK &lpar;bongocat, luna, crab, ocean-dream&rpar; | MC Technology](https://www.youtube.com/shorts/_dswDmpqY0A)
- [corne keyboard animaciones para teclado custom con QMK &lpar;bongocat y mas ...&rpar; | MC Technology](https://www.youtube.com/watch?v=w9Z_ODrKhvQ)
- [corne keyboard full wireless nicenano tutorial &lpar;guia facil&rpar; | MC Technology](https://www.youtube.com/watch?v=YVi7ROevBAI)
- [Ejecuta y depura código en VIM con SOLO 1 click + multiterminales | MC Technology](https://www.youtube.com/watch?v=uba3mR7RNhg)
- [Depurando en VIM con vimspector | MC Technology](https://www.youtube.com/watch?v=wIU6Roqmljs)
<!-- YOUTUBE:END -->

➡️ [more videos...](https://www.youtube.com/channel/UC_mYh5PYPHBJ5YYUj8AIkcw)

---

<h3 align="left"><img src="./src/estadistica2.gif" width="25px" height="25px"> GitHub Stats</h3>

<div>
  <a href="https://github.com/mctechnology17">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=mctechnology17&show_icons=true&theme=radical&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mctechnology17&layout=compact&langs_count=7&theme=radical"/>
</div>

![Snake animation](https://github.com/mctechnology17/mctechnology17/blob/output/github-contribution-grid-snake.svg)


<form action="https://www.paypal.com/donate" method="post" target="_top">
<input type="hidden" name="hosted_button_id" value="A9ZCHSS5K6SS8" />
<input type="image" src="https://www.paypalobjects.com/en_US/DK/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />

[zmk-config]: https://github.com/mctechnology17/zmk-config
[zmk-dongle-display-view]: https://github.com/mctechnology17/zmk-dongle-display-view
[zmk-oled-adapter]: https://github.com/mctechnology17/zmk-oled-adapter
[zmk-nice-oled]: https://github.com/mctechnology17/zmk-nice-oled

[niceview]: https://nicekeyboards.com/nice-view/
[oled]: https://keycapsss.com/keyboard-parts/parts/80/0.91-oled-lcd-display-128x32-ssd1306-i2c
[nice-view]: https://nicekeyboards.com/nice-view
[puchi_ble_v1]: (https://keycapsss.com/keyboard-parts/mcu-controller/202/puchi-ble-wireless-microcontroller-pro-micro-replacement?number=KC10157_SWITCH&c=18)
[seeeduino_xiao_ble]: (https://keycapsss.com/keyboard-parts/mcu-controller/212/seeed-studio-xiao-nrf52840-rp2040-esp32c3?number=KC10167_NRF)
[nice_nano_v2]: (https://nicekeyboards.com/nice-nano)
[keymap-editor]: https://nickcoutsos.github.io/keymap-editor/
[ZMK firmware]: https://github.com/zmkfirmware/zmk/
[ZMK documentation]: https://zmk.dev/docs/user-setup
[ZMK keycodes]: https://zmk.dev/docs/codes
[ZMK Discord]: https://zmk.dev/community/discord/invite

[qmk-config]: https://github.com/mctechnology17/qmk-config
[qmk_userspace]: https://github.com/mctechnology17/qmk_userspace

[git]: (https://github.com/git-guides/install-git)

[github]: https://github.com/mctechnology17
[twitter]: https://twitter.com/mctechnology17
[youtube]: https://www.youtube.com/c/mctechnology17
[instagram]: https://www.instagram.com/mctechnology17/
[facebook]: https://m.facebook.com/mctechnology17/
[reddit]: https://www.reddit.com/user/mctechnology17

[vim-executor]: https://github.com/mctechnology17/vim-executor
[vim-better-header]: https://github.com/mctechnology17/vim-better-header
[gm]: https://github.com/mctechnology17/gm
[vimtools]: https://github.com/mctechnology17/vimtools

[jailbreakrepo]: https://mctechnology17.github.io/
[uiglitch]: https://repo.packix.com/package/com.mctechnology.uiglitch/
[uiswitches]: https://repo.packix.com/package/com.mctechnology.uiswitches/
[uibadge]: https://repo.packix.com/package/com.mctechnology.uibadge/

[youtuberepo]: https://github.com/mctechnology17/youtube_repo_mc_technology

[youtube]: https://www.youtube.com/c/mctechnology17
[reddit]:https://www.reddit.com/user/mctechnology17
