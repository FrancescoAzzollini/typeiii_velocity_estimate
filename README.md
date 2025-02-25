# typeiii_velocity_estimate

A python class that determines velocity and acceleration of a type III solar radio burst emitter. The arguments here are: 'show' if you want velocity plots to be shown, 'Y' if you want to save the plot or 'T' if you want to show quantitues involved for  sanity check, i.e. lightcurves for highest and lowest frequencies (the red line shows chosen uncerteinty in flux, i.e. width of lightcurve at chosen height) and plot errors on velocities and accelerations. In this example, cdf files for PSP/lfr L3 data are used. The class works by inputting: 

type_III_lab(date, start_time, end_time, 'path_where_cdf_file_is_kept\\psp_fld_l3_rfs_lfr_' + path).dyn_spec('show', 'T', max_freq, min_freq, source-s/c angle, height/peak  where width of lightcurve is taken as uncerteinty in flux) 
