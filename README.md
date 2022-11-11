force_install_dir csgoserver <br /> 
login anonymous <br />
app_update 740 validate <br />


// Without pre-made cfg <br />
get5_check_auths 0 <br />
get5_kick_when_no_match_loaded 0 <br />
get5_creatematch <br />


// CFG load
get5_loadbackup get5_backup_match22_map0_prelive.cfg <br />
get5_loadbackup get5_backup_match10_map0_round7.cfg <br />


// With premade cfgs
get5_loadmatch first.cfg <br />
get5_loadmatch second.cfg <br />

// end match
get5_endmatch <br />


