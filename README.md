# Counter Strike Autoexec Generator

## This library is a simple autoexec generator for Counter Strike

Putting these files in your CS:GO cfg folder will allow you to generate an autoexec.cfg file with the settings you want.
</br>
Here is a list of the things that this library will do:

- Create FPS caps to reduce throughput latency and increase performance.
- Custom key binds.
- Reduce lag and server latency.
- Set preference to -128 tick servers.
- Better sound quality.
- Predictive audio.
- Custom radar (minimap).
- Custom crosshair.
- Utility crosshair.
- Crosshair color cycling.
- Custom viewmodel.
- UI color change.
- Reduced visual recoil.
- Changed in-game scoreboard to reduce visual clutter.

## How to use

1. Download the files in this repository.
2. Put the files in your CS:GO cfg folder.

The default location for the CS:GO cfg folder is:

```C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg```

3. Open Steam and right click on CS:GO. Select "Properties".
4. In the "General" tab, set launch options is on the bottom. 
5. Add the following to the launch options:

```-novid -nojoy -forcenovsync +exec autoexec.cfg```

6. Launch CS:GO and enjoy!

- You may also run the autoexec.cfg file in-game by opening up the console and typing ```safe```