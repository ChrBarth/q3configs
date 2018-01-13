# b0nest0rm's quake3-configs

* main q3-config: `baseq3/c.cfg`

   This is the main config with all the key bindings, graphics settings etc.

* cpma-configs: `cpma/*.cfg` and `baseq3/c_cpma.cfg`

   `c_cpma.cfg` adds some additional settings only available in cpma. It first loads `c.cfg` then overrides/adds some settings for cpma gameplay (enemymodel etc.)

   `c_1v1.cfg`, `c_tdm.cfg`,...: the configs for different game modes

* cpma-gamemodes (ctf only at the moment) can be found in `./cpma/modes/`

* the settings for some maps in certain gamemodes can be found in `./cpma/cfg_maps`
