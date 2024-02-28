# Projects

Just my own repositories graph

*((cuz i forgor))*

blocks are clickable ⬇

```mermaid
flowchart LR

  subgraph Projects
    direction TB
    base(["Projects"])

    player_api["PlayerAPI"]
    media_control["MediaControl"]
    audio_vis["PySerialAudioVisualizer"]
    saaba["saaba"]
    pydeck["PyDeck"]

    v_game["pygametest"]
    danmaku["Danmaku"]

    click media_control href "https://github.com/virashu/media_control"
    click audio_vis href "https://github.com/virashu/PySerialAudioVisualizer"
    click saaba href "https://github.com/virashu/saaba"
    click pydeck href "https://github.com/virashu/pydeck"
    click v_game href "https://github.com/virashu/pygametest"
    click danmaku href "https://github.com/virashu/Danmaku"

    base --> media_control
    base --> player_api
    base --> saaba
    base --> audio_vis
    base --> pydeck

    base --> v_game
    base --> danmaku

    v_game -.- danmaku
    player_api -.- media_control
    saaba -.- media_control
    saaba -.- audio_vis
    saaba -.- pydeck
  end

  subgraph Linux
  direction TB
    dwm["dwm"]
    py_theme["pytheme"]
    py_status
    dotfiles
    dmenu
    xmenu
  end

```