force_install_dir csgoserver
login anonymous
app_update 740 validate


// Without pre-made cfg
get5_check_auths 0
get5_kick_when_no_match_loaded 0
get5_creatematch


// CFG load
get5_loadbackup get5_backup_match22_map0_prelive.cfg
get5_loadbackup get5_backup_match10_map0_round7.cfg


// With premade cfgs
get5_loadmatch first.cfg
get5_loadmatch second.cfg

// end match
get5_endmatch


