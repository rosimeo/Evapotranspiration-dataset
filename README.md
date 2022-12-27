# Evapotranspiration-dataset
A dataset for prediction of amount of evapotranspiration.

The paper on this data and on the task of prediction by Machine Learning is published at ACM Symposium of Applied Computing 2023, entitled:

"Multivariate Time Series Evapotranspiration Forecasting using Machine Learning Techniques" by Chalachew Muluken Liyew, Rosa Meo, Elvira Di Nardo, Stefano Ferraris, University of Torino, and Politecnico di Torino, Italy

The complete dataset contains the following features (sampled every 30 minutes) from 2014 to 1st October 2017:

date (in dd/mm/yyyy)

time (hh:mm)

days (order number of the day)

DOY (Day of the Year: order number)

daytime (night or day)

Tau (in kg/m^2 s^-1)

qc_Tau

rand_err_Tau (in kg/m^2 s^-1)

H (in W/m^2)

flag_H_EP_DR

rand_err_H (in W/m^2)

LE (in W/m^2)

flag_LE

rand_err_LE (in W/m^2)

co2_flux (in umol/m^2 s^-1)

flag_CO2_flux_EP_DR

rand_err_co2_flux (in umol/m^2 s^-1)

h2o_flux (in mmol/m^2 s^-1)

qc_h2o_flux

rand_err_h2o_flux (in mmol/m^2 s^-1)

H_strg (in W/m^2)

LE_strg (in W/m^2)

co2_strg (in umol/m^2 s^-1)

h2o_strg (in mmol/m^2 s^-1)

co2_v.adv (in umol/m^2 s^-1)

h2o_v.adv (in mmol/m^2 s^-1)

co2_molar_density (in mmol/m^3)

co2_mole_fraction (in umol/mol)

co2_mixing_ratio (in umol/mol)

co2_time_lag (in s)

h2o_molar_density (in mmol/m^3)

h2o_mole_fraction (in mmol/mol)

h2o_mixing_ratio (in mmol/mol)

h2o_time_lag (in s)

sonic_temperature (in degK)

air_temperature (in degK)

T_air_meas (in degC)

air_pressure (in hPa)

air_density (in kg/m^3)

air_heat_capacity (in J/kg K^-1)

air_molar_volume (in m^3/mol)

AET (actual evapotranspiration, in mm)

water_vapor_density (in kg/m^3)

e_LI7500 (in hPa)

es_LI7500 (in hPa)

specific_humidity_LI7500 (in kg/kg)

RH_LI7500 (in %)

VPD_LI7500 (in Pa)

Tdew_LI7500 (in degK)

e_HMP (in hPa)

es_HMP (in hPa)

VPD_HMP (in hPa)

RH_HMP (in %)

u_unrot (unrotated wind, in m/s)

v_unrot	(in m/s)

w_unrot (in m/s)

u_rot (rotated wind, in m/s)

v_rot	(in m/s)

w_rot	(in m/s)

wind_speed	(in m/s)

max_wind_speed	(in m/s)

wind_dir (in deg)

yaw (Rotation angles tilt correction, in deg)

pitch	(in deg)

roll (in deg)

ustar (Turbulence, wind flow, wyngaard errors, in m/s)

TKE	(in m^2/s^2)

L	(in m)

X.z.d..L	

bowen_ratio	

stability_class	

velocity_class	

T. (in degK)

err_wT	

err_wh2o	

err_wco2	

flagerr_wT	

flagerr_wh2o	

flagerr_wco2

model (footprint, in Hsieh)	

x_peak (in m)	

x_offset (in m)

x_10.	 (in m)

x_30.	 (in m)

x_50.	 (in m)

x_70.	 (in m)

x_90.  (in m)

un_Tau (Uncorrected fluxes and spectral correction factors, in kg/m s^-1)

Tau_scf	

un_H	(in W/m^2)

H_scf	

un_LE	(in W/m^2)

LE_scf	

un_co2_flux	(in umol/m^2 s^-1)

co2_scf	

un_h2o_flux	(in mmol/m^2 s^-1)

h2o_scf

spikes_hf (Statistical flags)

amplitude_resolution_hf	

drop_out_hf	

absolute_limits_hf	

skewness_kurtosis_hf	

skewness_kurtosis_sf	

discontinuities_hf	

discontinuities_sf	

timelag_hf	

timelag_sf	

attack_angle_hf	

non_steady_wind_hf

u_spikes (Spikes)

v_spikes	

w_spikes	

ts_spikes	

co2_spikes	

h2o_spikes

chopper_LI.7500 (Diagnostic flags LI7500)

detector_LI.7500	

pll_LI.7500	

sync_LI.7500	

mean_value_LI.7500	

GC	

flag_GC	

flag_spike_momflux	

flag_spike_H	

flag_spike_LE	

flag_spike_CO2	

flag_ampres_momflux	

flag_ampres_H	

flag_ampres_LE	

flag_ampres_CO2	

flag_dropout_momflux	

flag_dropout_H	

flag_dropout_LE	

flag_dropout_CO2	

flag_skewkurt_momflux	

flag_skewkurt_H	

flag_skewkurt_LE	

flag_skewkurt_CO2	

flag_discont_momflux	

flag_discont_H	

flag_discont_LE	

flag_discont_CO2	

fiNANlflag_HLE_prc	

fiNANlflag_CO2_prc	

fiNANlflag_momflux_prc	

fiNANlflag_H_prc	

fiNANlflag_h2oflux_prc	

fiNANlflag_LE_prc	

fiNANlflag_momflux_prc_unc	

fiNANlflag_H_prc_unc	

fiNANlflag_h2o_prc_unc	

fiNANlflag_LE_prc_unc	

fiNANlflag_CO2_prc_unc

u_var (Variances, covariances, advanced statistical flags, in m^2/s^2)

v_var (in m^2/s^2)

w_var	(in m^2/s^2)

ts_var	(in degK^2)

co2_var	(in umol^2)

h2o_var	(in mmol^2)

w.ts_cov	(in degK m/s)

w.co2_cov	(in umol/m^2 s^-1)

w.h2o_cov (in mmol/m^2 s^-1)

flag_wd	

flag_spikes_hf_u	

flag_spikes_hf_v	

flag_spikes_hf_w	

flag_spikes_hf_ts	

flag_spikes_hf_co2	

flag_spikes_hf_h2o	

flag_absolute_limits_hf_u	

flag_absolute_limits_hf_v	

flag_absolute_limits_hf_w	

flag_absolute_limits_hf_ts	

flag_absolute_limits_hf_co2	

flag_absolute_limits_hf_h2o	

flag_ampres_u	

flag_ampres_v	

flag_ampres_w	

flag_ampres_ts	

flag_ampres_co2	

flag_ampres_h2o	

flag_dropout_u	

flag_dropout_v	

flag_dropout_w	

flag_dropout_ts	

flag_dropout_co2	

flag_dropout_h2o	

flag_skewkurt_u	

flag_skewkurt_v	

flag_skewkurt_w	

flag_skewkurt_ts	

flag_skewkurt_co2	

flag_skewkurt_h2o	

flag_discont_u	

flag_discont_v	

flag_discont_w	

flag_discont_ts	

flag_discont_co2	

flag_discont_h2o

Rg (Radiation, in W/m^2)

Rg_interp	(interpolated, in W/m^2)

Rn (in W/m^2)	

SR01Dn_Avg	(in W/m^2)	

SR01Up_Avg	(in W/m^2)	

IR01UpCo_Avg	(in W/m^2)	

IR01DnCo_Avg	(in W/m^2)	

airTC_NR01	(air temperature, in degree Celsius)

S_canopy	(in W/m^2)

S	flag_Rn	(in W/m^2)

flag_dTs	

flag_G	

flagprec

CTT (Surface and soil, temperature in degC)

VWC_10_20	(in m^3/m^3)

VWC_40	(in m^3/m^3)

dTsoil	(temperature in degC)

Tsoil	

ET_reconstr	

Bo	

EF

LE_gapfilled (Filled fluxes, filled and nonfilled AET corrected, in W/m^2)

H_gapfilled	(in W/m^2)

co2_flux_gapfilled (in umol/m^2 s^-1)	

LE_gapfilled_qc	

H_gapfilled_qc	

co2_flux_gapfilled_qc	

AET_nongapf_mmh	(in mm/h)

AET_nongapf_mmhalfh	(in mm/30 min)

AET_nongapf_kgm2s	 (in kg/m^2 s^-1)

AET_mmh	(in mm/h)

AET_mm halfhour (mm/30 min)

AET_kgm2s	(in kg/m^2 s^-1)

Bo_gapfilled	

EF_gapfilled

