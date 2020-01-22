C-ROADS Change Log
===============================

**1 Feb 17**

**v5.003.084**

-  Updated Reference Scenario:

   -  Uses newly available GDP data in 2011 PPP through 2015, CO2 FF
	  data through 2015, and Land use CO2 through 2014.

   -  Uses CO2 per GDP rates as determined from recent trends over the
	  past decade as initial projected rates and shorted, as warranted,
	  the time to converge those rates

   -  Added structure to HFCs Reference emissions to reflect Kigali Deal

   -  Resulting Reference temperature in 2100 is now 4.2 Deg C

-  Updated starting years to 2017.

-  Removed the graphical input entry feature.

**10 Nov 16**

**v5.002.082**

-  Inputs for Deforestation and Afforestation are now a 0-100% scale,
   replacing the 0-1 scale.

-  When using World Climate mode in either 6 or 3 region, the default
   graph for emissions is CO2 Fossil Fuel Emissions.

-  Added graphs for Deforestation and for afforestation to the World
   Climate simulation mode.

**25 May 16**

**v5.001.082**

-  Change input for Deforestation in World Climate mode—The input for
   deforestation is now set up as effort to prevent deforestation, a 0
   to 1 scale. Input a value between 0 and 1 to adjust the level of CO2
   emission reductions in land use and forestry.

   -  0 – represents no change from the business as usual scenario and
	  yields constant emissions (5.4 GtonsCO2/year) from deforestation
	  through 2100.

   -  0.5 – yields a drop of 50% emissions by 2050, and then remains at
	  that level until 2100.

   -  1 – is the equivalent of eliminating all deforestation globally by
	  the year 2050.

-  Changes to the Welcome screen and dedicated World Climate 6-region
   and 3-region modes.

-  From the Program settings screen you may set the model to open with
   the graph for “Temperature and Goal” graph to either °F or °C.  When
   the simulation is running you still have the ability to shift between
   °F and °C from the “Settings” tab.

-  In the “Settings” tab you may show or hide the effects of the INDCs
   from COP21 (last updated 4-Apr-16).

-  The final temperature in 2100 is displayed at the top of the screen
   in both °F and °C.

-  The default Reference Scenario is now calculated to be consistent
   with IPCC’s Fifth Assessment Report (AR5) and captures the
   relationships of population, GDP per capita, and emissions per GDP. 
   Population defaults to use the UN’s medium fertility projections (UN,
   2015).  GDP is consistent with the Shared Socioeconomic Paths (SSPs).
   It is determined as the product of population and GDP per capita,
   which, for each of the model’s 20 regions, is a function of its
   starting value from history and projected rate of change.  These
   projected rates start at levels consistent with historical data and
   converge to 1%/year over region-specific times aimed to achieve long
   term convergence of GDP per capita.

-  Comparable to GDP per capita, Reference Scenario emissions of each
   GHG are consistent with Representative Concentration Pathway 8.5 (RCP
   8.5) and are determined as the product of population, GDP per capita,
   and emissions per GDP.   Likewise for GDP per capita, emissions per
   GDP of each GHG is a function for each of the model’s 20 regions of
   its starting value from history and projected rate of change.  The
   starting rate of each region converges to a minimum GHG-specific rate
   over times aimed to achieve long term convergence of emissions per
   GDP.

**04 Dec 15**

**v4.027.076**

-  Corrected initialization files for graphical inputs

-  Created new Excel file for user inputs, “User Scenario v4 027.xls”

**03 Dec 15**

**v4.027.075**

-  Updated the settings files for INDCs to the most recent pledges.

-  Added a feature that will use a settings file (.cin) to create a
   results file (.vdf). This is a new button on the ‘Welcome’ page—
   ‘Settings —>Results’— which simplifies the updating of results files
   for use in Uncertainty analysis.

**24 Nov 15**

**v4.027.074**

-  Graph line thickness may be adjusted from the ‘Settings’ Tab. This
   applies to small and large graphs.

-  Removed obsolete reference scenarios– EMF22 series and SRES series.

**12 Nov 15**

**v4.026.072**

-  Corrected several minor graph labeling issues

-  Added graphs to 3 region version for Cumulative Fossil Fuel CO2 per
   Capita and Cumulative CO2 equivalents per Capita

**5 Nov 15**

**v4.026.071**

-  C-ROADS has been calibrated to the latest Intergovernmental Panel on
   Climate Change (IPCC) report (AR5) and now uses the IPCC’s RCP8.5
   scenario as the default or reference scenario representing business
   as usual.

-  Settings files have been packaged with C-ROADS that allow users to
   load the intended nationally determined contributions (INDCs) that
   countries have submitted for the upcoming climate negotiations.

-  We have also included a 3-region World Climate mode that divides the
   world into Developed Countries, Developing A Countries, and
   Developing B countries for the World Climate Exercise.

-  The lower limit of climate sensitivity can now go as low as 1.5°C
   (rather than 2°C).

-  Graphs are provided with comparisons between C-ROADS projections for
   temperature and CO2 concentration to those of RCP 8.5, 6.0, 4.5 and
   2.6.

-  Population scenarios that match the UN may be adjusted.

-  Historical data was updated to include most recent available, and all
   start years were updated to be 2015.

-  The Excel and Non-Excel input versions have been combined in a single
   C-ROADS version.

**28 Jul 14**

**v3.015.02X**

We have created a modified version of C-ROADS, v3.015.02X that does not
require Excel to run. Either version is available from the download
link. The default download is the non-Excel version.

**10 Jul 14**

**v3.014.040**

Corrected a miss-assigned input slider for the Goal line for CO2e on the
Atm CO2e and Goal graph.

**29 Apr 14**

**v3.014.039**

Corrected an issue within the World Climate setup mode whereupon
returning from “Load/Unload Run” or “Reset to Reference” the WCE setup
mode reverted to normal C-ROADS use with all the tabs on the input pane
active rather than remaining in the special World Climate mode.

Edited the help text related to the Sensitivity settings.

**6 Dec 13**

**v3.014.xxx**

The historical data sets for CO2 fossil fuel emissions and the inclusion
of recently made available historical CO2 bunker fuel emissions data
have been updated in this release. Additionally, other variables have
been updated with more recent data, including population and GDP, Mauna
Loa data CO2 concentration data, and GISS other forcings. The GISS data
were also slightly updated, which required a readjustment to the MAGICC
historic values, where the adjustment brings the mean over 1880-1999 to
be the same between both data sets.

**25 Nov 13**

**v3.012.035**

Graph colors fixed in “Contributions”

**4 Feb 13**

**v3.012.xxx**

**Units change from MEX to PPP**

| In C-ROADS, GDP is represented in units of $2010 MEX/year (market
  exchange rate)
| except when you choose “A1FI with EIA allocations,” the top menu item
| for the reference scenarios. For this selection the units
  are expressed as
| $1990 PPP/year (purchasing power parity).  The “User Scenario v3
| 012.xls” sheet which is used when you choose “User Reference
| Scenario”, has been updated to reflect that the GDP reported therein
  is
| now M $2010 MEX/year.

**24 Sep 12**

**v3.008.xxx**

**Additional graphs**

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image003.png|

We have added graphs for CO\ :sub:`2` equivalent emissions by country
and global to the “CO\ :sub:`2` Equiv” graph menu and have relocated
“Forestry Net Emissions by Country” graph from the “Land Use” menu to
the “CO\ :sub:`2` Equiv” menu to follow the general rule that the graphs
on the left are more emissions related and the graphs on the right are
more results- or impact-related.

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image005.png|\ |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image007.png|

Three new graphs are also present in the right graph pane under the menu
“GHG concs”, which was formerly labeled “CO2 & CO2e”. These are for the
atmospheric concentrations of CH4, N2O, and atmospheric CO2e and the
user specified goal for CO2e. The goal for CO2e is set on the “Settings”
pane using the “Atmospheric CO2e Goal” controls.

**Modification to the World Climate input table**

When a country/bloc is set for Manual, Excel, or Graphical input, the
table cells representing it in the World Climate input table are
disabled for input and grayed. In the example shown in the figure, both
the US 6R and India 6R are set to Manual or Excel input respectively and
their respective rows are disabled. The settings for Deforestation for
the US, EU, and China are always disabled and grayed out.  The remaining
forestry inputs are either displayed as in the figure when WCE Forestry
inputs are active or are grayed/disabled when Land-use Forestry inputs
are active.  Inputs to table cells are prevented when the cells are
disabled.

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image009.png|

**Revised Historical data added CO\ 2**

The changes in CO\ :sub:`2`\ emissions are very slight and are due to a
revision released by the Carbon Dioxide Information Analysis Center
(CDIAC).  The updated reference for this is:

Boden, T.A., G. Marland, and R.J. Andres. 2011. Global, Regional, and
National Fossil-Fuel CO2 Emissions. Carbon Dioxide Information Analysis
Center, Oak Ridge National Laboratory, U.S. Department of Energy, Oak
Ridge, Tenn., U.S.A. doi 10.3334/CDIAC/00001_V2011,
cdiac.ornl.gov/ftp/ndp030/CSV-FILES/nation.1751_2008.csv.

**Other GHGs**

The changes in the emissions of other GHGs are due to the more complete
national data released by EDGAR 4.2. Before this update,
CH\ :sub:`4,`\ and N\ :sub:`2`\ O data relied on allocation between
countries consistent with data by MIT’s Joint Program on the Science and
Policy of Global Change (JPSPGC) Technical Note No. 8 (2006) but scaled
to the global emissions provided by Stern and Kaufmann (1998) for CH4
and EDGAR-HYDE 1.4 (Van Aardenne *et al.*, 2001, adjusted to Olivier and
Berdowki, 2001) for N\ :sub:`2`\ O emission data.  Those data spanned
through 1995.

Similarly, MIT’s JPSPGC Technical Note 8 (Asadoorian *et al.,* 2006)
provides the historical emissions for PFCs and SF\ :sub:`6` by country.
HFCs are considered as nine of the predominant individual HFC gases. The
historical data for HFCs were based on MIT’s JPSPGC Technical Note 8
(Asadoorian *et al.,* 2006) HFC-134a equivalent emissions, which were
allocated between the different HFC types according to the ratio of the
different types at the earliest year of A1FI projections, i.e., in the
year 2000.

Now, EDGAR 4.2 provides the historical emissions from 1970-2008 of
CH\ :sub:`4`, N\ :sub:`2`\ O, and F-gases (including PFCs, SF6, and the
nine predominant HFC types).  Pre-1970s data still relies on the former
methodology.  Globally, the results are fairly consistent except for
N\ :sub:`2`\ O, which is approximately 17% less for the EDGAR 4.2 data
than it was using the global data by EDGAR-HYDE 1.4 (Van Aardenne *et
al.*, 2001, adjusted to Olivier and Berdowki, 2001).

The evaluations of Reference Scenarios as determined from downscaling
using the updated and more reliable historical data reveal that in many
cases the regional consistency with SRES and EMF regions is indeed
improved.  However, there are also many cases where it appeared better
and the bridge from historical to projected emissions was smoother when
we used the less complete data, which relied on more assumptions
including filling in the gap of years between 1995 through 2010 using
those models’ projections.  However, SRES and EMF projections were
generated before the data occurred, and history has not always been
consistent with those projections.  Our task in downscaling from those
models has been to accurately reflect history with the best available
data and bridge those with the SRES/EMF projections.

**Population projections**

The population projections under the alternate Reference Scenario have
been slightly updated to reflect a few corrections in the regional
assignment of countries listed by the United Nations, the source of the
alternate population reference scenario.

**Bug fixes**

In the 6-region aggregation, when changing one country/bloc to World
Climate inputs, the Forestry/Land Use inputs were also changing the to
World Climate mode. This has been decoupled so that Forestry/Land Use
inputs must be explicitly changed to World Climate mode if desired. The
exception to this occurs when the “World Climate Setup” button on the
Welcome/Main screen is clicked which sets all regions to World Climate
as well as sets the Forestry/Land Use inputs for World Climate.

We also corrected a labeling error in the y-axis label on graphs for
Cumulative Fossil Fuel CO\ :sub:`2` from PPM to GTon CO\ :sub:`2`\ in
the Contribution Analysis.

**Dataset Control**

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image011.png|

When the Dataset Control dialog is dismissed, C-ROADS remains the active
window. Whenever the current_run is not active, there is a message to
that effect displayed below the graph legends and below the control
panel.

**Set X-axis for Graphs feature while in “Review Run(s)” mode**

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image013.png|\ |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image015.png|

The “Settings” tab was not active when C-ROADS was used in “Review
Run(s)” mode preventing access to the **Set X-axis for Graphs** feature
that allows changing the x-axis. This has been corrected and the x-axis
may be changed in “Review Run(s)”, “Load Saved Run”, and “Create New
Run” modes. There is a reminder message at the bottom of the control
area to guide the user back to the current run when desired. 

**6 Mar 12**

**v3.005.018**

**Excel and graphical inputs in 1-region/Global mode**

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/clip_image004.png|

We have added the ability to input Fossil Fuel CO\ :sub:`2` emissions
targets using the Excel spreadsheet, User Scenario v3 005.xls, as well
as via the graphical input mode\ **\***. Setting inputs for 1-region is
now the same as for the 6-region and 15-region spreadsheet input.

**Additional graphs**

Two additional graphs have been added to the graph viewing panes. Under
the “CO\ :sub:`2` Emissions” menu on the left graph pane, two Global
Cumulative Fossil Fuel CO\ :sub:`2` Emissions graphs are available
displayed either in GTons Carbon or as GTons CO\ :sub:`2`. These new
graphs are available at any of the C-ROADS aggregation levels.

**Resize to Screen Size Option**

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/clip_image006.png|

If you open the C-ROADS Directory within Windows Explorer, you will see
both “C-ROADS v3.VNP” and “C-ROADS v3 – resize.VNP.” Selecting the
“C-ROADS v3 – resize” option will open C-ROADS in a mode which scales
the C-ROADS User Interface to fit a larger or smaller screen size. This
is especially helpful if you using a screen that is smaller than the
minimum 1024 x 768 that the normal C-ROADS interface is designed to fit.
The screen rescaling is not merely a zoom of the screen and as such some
items do not scale as well as others. Nevertheless this option can be
helpful with small screens. For projection purposes, we recommend
changing the computer’s screen resolution to closer to the projector’s
resolution to make the C-ROADS native 1024×768 image more visible. This
preserves the quality of the user interface.

**Dataset Control help dialog**

When you click on the “Load/Unload Run” button, there is now a help file
to guide your resizing of the “Dataset Control” dialog. It is there if
you need it, and may be ignored if you don’t. When you dismiss the
“Dataset Control” dialog, the help screen also closes.

**Adjust x-axis maximum and minimum on graphs**

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/clip_image008.png|

In the **Settings** pane there is a new adjustment for graphs, **Set
X-axis for Graphs**, which contains a pair of input boxes that allow you
to change the displayed years on those graphs that normally display from
2000-2100. This feature may be useful if you want to focus attention on
near term goals such as 2020 targets or 2050 targets by only showing the
relevant years of the graph or historical portions of particular data.

**Bug fixes**

A bug was repaired that caused a saved run which was at 1-region/Global
resolution and opened using “Load saved run” to open without displaying
the Emissions targets settings on the screen.

If the Reference scenario was not set to the default, SRES A1FI MINCAM,
on the Welcome/Main view and a saved run was loaded that used the
default as the reference scenario, the run would be loaded with the
incorrect reference scenario.

**1 Feb 12**

**v3.0**

**Model Sensitivity testing with the new Sensitivity tab**

You can now test the sensitivity of C-ROADS results to eleven key
parameters in the Sensitivity pane. They include:

-  climate sensitivity

-  ocean mixing

-  CO2 fertilization

-  biomass loss from afforestation

-  carbon cycle: land and Ocean Uptake

-  methane Emissions from biological activity

-  methane emissions from permafrost and clathrates

-  temperature threshold for permafrost and clathrates

-  Emissions/GDP: Ref Scenario

-  Emissions/Capita: Ref Year

-  Emissions/Capita: Ref Scenario

**Changes in the Emissions Targets input controls– Additional Target
types**

On the Emissions Targets tab there are three new target types:

-  Emissions/GDP: Ref Scenario

-  Emissions/Capita: Ref Year

-  Emissions/Capita: Ref Scenario

We have renamed the menu choices to help point out the differences and
similarities.

**Population and GDP controls**

In the new “Population and GDP” tab, assumptions within the selected
Reference scenario about population and GDP may be adjusted using the
controls found in this new input pane.

**Additional output graphs**

Six additional graphs have been added to the graph viewing panes. Under
the “ Other” menu on the left graphs pane there are country/bloc level
graphs for Population, GDP, GDP per capita and Gross World Product per
capita. On the right graph pane, under the “per Capita” menu there are
two new graphs for Global emissions per capita and Global emissions per
Gross World product. These two variables are also present on the
corresponding country/bloc level graphs as points of reference.

**New World Climate Exercise tab**

We have added controls to enable C-ROADS to be used for facilitating the
World Climate role playing exercise. With the press of a button on the
main page you can set up a 6-Region simulation and activate the controls
on the World Climate Exercise pane and deactivate most of the other
input controls to provide a clean, simplified version of C-ROADS for use
with World Climate. The controls allow World Climate type inputs of
“Growth Stop Year,” “Decline Start Year,” and “Annual emissions
reduction (%/year)”. Forestry inputs are also controllable as a 0-1
index for deforestation and afforestation by country or bloc.

For the advanced C-ROADS user, the controls for the World Climate
Exercise may be activated after initiating a 6-region run using the
“Create New Run” button or by loading a previously saved 6-region run
using the “Load Saved Run” button. Either will allow access to all
C-ROADS control elements during a World Climate session as well as the
reference scenario you have chosen from the menu. Emissions for
individual countries may be entered in the standard “manual” mode rather
than using the World Climate style entry allowing extensive flexibility
in your use.

**Recalibration of the Reference Scenarios**

We recently updated the Reference Scenarios (RS) to improve our
methodology for downscaling from the more spatially aggregated data
sources, i.e., SRES scenarios and EMF22 models. As a result, the global
projections for BAU emissions remain largely unchanged but the
allocation of future BAU emissions between C-ROADS regions has shifted.
Specifically, our new default, which remains based on SRES A1FI, now has
a greater share of the global emissions coming from the Developed and
Developing non-MEF regions. As before, the user can choose among the
suite of reference scenarios or base model runs on a customized,
user-designed reference scenario.

**10 Aug 11**

**v2.154b.70**

**Design changes to the Main/Welcome screen**

We have modified the Main/Welcome screen with some changes in button
placement to emphasize the precedence of button function. Buttons and
menus are now grouped in three categories: Settings, Simulation, and
Post-simulation analysis.

|Design Changes to Main - Welcome Screen|

**Settings**

The **Set Graph Defaults** button has moved under
the **Settings** heading which is more appropriate to its functional
role.

**Simulation**

There are two ways to “enter” a simulation, **Create New
Run** and **Load Saved Run**. **Create New Run** starts a new simulation
run using the User-specified settings from the Aggregation level and
Reference Scenario drop down menus and the simulator default settings
for all input controls.

You may also start a simulation based on a previously saved run
using **Load Saved Run**. This will start a simulation with all of the
simulator input control settings you had set previously when you saved
the simulation, including the Aggregation level and the Reference
Scenario source. You may make changes or modifications to the input
controls of the simulation and **Save Run** again to preserve the run in
its new state which is comprised of any unchanged control settings from
the starting file and any new setting of the input controls— starting
settings plus changes. This also allows you to create a favorite
starting  set of settings that you use as the basis for your “new runs”
even a simple as, for example,  “15-region, User Defined Scenario
baseline.”

We have removed the **Update Run** function as it did not add to the
capabilities provided by **Load Saved Run**.

**Post-simulation analysis**

Each of the **Post-simulation Analysis** functions requires a saved
simulation file as its input. These are the <filename.\ **vdf**> files
that you see in the “Simulation Output” and other directories.

**Contribution Analysis** takes a previously saved C-ROADS-CP run and
performs a leave-one-out analysis of the global data to determine the
contributions of each country/region to Cumulative Fossil Fuel
Emissions, CO2 ppm, Temperature, and Radiative Forcing. **Uncertainty
Analysis** takes a previously saved run and performs an
uncertainty/sensitivity analysis using an analysis toolset file and
displays the results for multiple variables. **Review Run(s)** is
unchanged from previous versions of C-ROADS-CP but the button has been
moved from **Simulation**\ to **Post-simulation Analysis **\ because,
functionally, it is an analysis of previously created simulation
output. **Export Dataset** remains unchanged and creates an Excel file
containing the data from the variables displayed on the graphs.

**1 region- Global aggregation**

There is a new option for the aggregation setting, “1 region- Global.”
Selecting this and choosing **Create New Run** will start a simulation
in which the Emissions Targets, Non-CO2 GHGs, and Land-use Emissions
controls affect emissions and land-use for the entire world. The
1-Region level of aggregation provides a means for a “quick sketch” to
explore the dynamics and sensitivities of different changes to user
inputs.

**Changes in the input controls**

**Settings tab**

Several of the settings have been moved to their relevant
tabs—Deforestation and Afforestation baseline settings to the **Land-use
Emissions **\ tab and the settings for Non-CO\ :sub:`2` GHGs to the
new **Non-CO\ 2 GHGS **\ tab.

**Emissions Targets tab (formerly Fossil Fuel CO2 emissions)**

The **Fossil Fuel CO\ 2 Emissions** tab has been renamed as
the **Emissions** **Targets** tab. This change reflects the nature of
the controls on this tab. These controls, by default, control emissions
of all Kyoto Protocol greenhouse gases, GHGs. This default behavior is
changed depending on the setting of the **Non-CO\ 2 GHGs** controls
(below). When the **Non-CO\ 2 GHGs** control is set to its default
setting to follow  “Emissions Targets”, the three emissions targets and
the post target controls affect all Non-Land use emissions— Fossil fuel
CO\ :sub:`2` emissions plus non-CO\ :sub:`2`\ GHG emissions. When
the **Non-CO\ 2 GHGs** control is set to follow “Reference scenario
non-CO\ :sub:`2` GHG emissions”, the **Emissions Target** tab controls
affect only Fossil fuel CO\ :sub:`2` emissions; the non-CO2 GHG
emissions are controlled by the active Reference scenario under these
conditions.

The “Post target” setting determines how emissions will behave after the
final target year is passed. There are 4 post target settings:  Cap at
target level, Continue rate to target, Resume Reference Scenario and
Specify rate. The Post target behavior is itself determined by the
selected target type: OFF, Ref year, Ref Scenario or Carbon Intensity.

The default behavior, “Cap at target level” depends on whether the
target type was set by Reference year, Reference scenario or by Carbon
Intensity. When you select a target type of “Reference year”, when the
target year is achieved the emissions remain constant at the target year
value. If you have chosen a “Reference scenario” target type, when the
target year is achieved the emissions will resume at the rate defined by
the active Reference scenario. Finally when you choose a target relative
to “Carbon intensity”, when the target year is achieved the carbon
intensity will remain capped at the level reached in the target year.
 Post target setting applies to the last target type setting.

For the remaining three settings of post target rate, all three target
types behave in the same manner regardless of which target type you use:

Continue rate to target— the emissions rate will follow the same rate
post target as it followed to hit the target.

Resume Reference Scenario— after the target is reached, the emissions
rate will resume the rate defined by the active Reference scenario.

Specify rate— you may set the post target rate at a fixed rate between
10%/year and -10%/year.

**Precedence of Reference Scenario vs. User settings. **

For 6 and 15 region, if the Reference Scenario rate of reduction is
greater than specified by the user, the Reference scenario becomes the
cap. An example is shown in the figure. The reference scenario behavior
is the green line. Reduction starting in 2012 (1\ :sup:`st` up-arrow) to
25% below 2000 levels  by 2050 (2\ :sup:`nd` up arrow) is the red line.
From 2012 until ~2020 (first down arrow) the Reference scenario is less
than the User scenario so the Reference scenario predominates. From 2020
until 2055 (2\ :sup:`nd` down arrow) the User scenario is less than the
Reference scenario and the User scenario predominates. At 2050, the
emissions rate becomes constant at the user-specified 2050 level until
approximately 2055 when the Reference scenario is lower than the
user-specified 2050 level and the Reference scenario again predominates.

If instead of 25% below 2005 levels, the user had specified 0% below, or
2005 levels, the Reference Scenario would always predominate and there
would appear to be no model response when in fact the model response is
to use the lesser of the Reference scenario or the user-specified
scenario.

**Non-CO\ 2 GHGs tab**

This new tab is a new location for the control from
the **Settings** tab, “Non-CO\ :sub:`2` GHGs.” The options have been
renamed from “Follow CO\ :sub:`2`\ emissions” and “Reference Scenario”
to “Fossil Fuel CO\ :sub:`2` emissions targets” and “Reference Scenario
Non-CO\ :sub:`2` GHG Emissions”. Their functions remain the same. There
is a third new capability, “Scaled Reference Scenario
Non-CO\ :sub:`2` GHG Emissions”. This setting allows you to create a
scaled version of the reference scenario that will apply to the
non-CO\ :sub:`2` GHGs in the reference scenario.

In addition to the new “Scaled Reference Scenario Non-CO\ :sub:`2` GHG
Emissions” capability, these settings have been disaggregated to match
the aggregation level of the run: 1 region, 6 region or 15 region. They
were previously only global. There are table inputs and individual
country inputs available for 6- and 15-region aggregation.  An example
of the 6-region input below shows the active buttons when the “Scaled
Reference Scenario Non-CO\ :sub:`2` GHG Emissions” is selected for a
country or region- note the red dots.

The setting of the Non-CO\ :sub:`2` GHG switch changes the nature/target
of the controls on the **Emissions Targets** tab as described above
under **“Emissions Targets.”**

**Land use emissions tab**

The baseline settings for Deforestation and Afforestation have moved
from the **Settings** tab to this tab so all the Land use emissions
settings are grouped together. There is no change in their function.
When the Land use Global settings input pane is visible, these settings
are active. Conversely, when the country/region settings are visible,
country/region settings are active. The settings that were active at the
time of a “\ **Save Run**\ ” will be active if you reopen a saved run,
but both global and country/region settings are saved.

**Non-CO\ 2 forcings tab**

This is a new function. You may set, using graphical inputs, three
non-CO\ :sub:`2` forcings: 1) **Organic Carbon, Black Carbon, and Bio
Aerosols**, 2) **Solar and Albedo**, and 3) **Ozone
Precursor** **forcings**. They are activated by a check box. Saving the
model run will save the settings of the graphical inputs as well as the
state of the check box.

**10 Mar 11**

**v2.148a.46**

|/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/directory-structure.png|

**Directory structure added**

In release v2.148a.46 we have added a new directory structure that will
help separate user–generated files from C_ROADS CP files created during
installation. Previously, the two file genera were co-mingled and
C-ROADS-CP would only read files from specified directories making it
complicated for users to maintain any sub-directory organization of user
files. The folder view of the new structure is shown here. The default
location when savings simulation results is the “Simulation Output”
folder. Users can create additional organization in this folder,
depicted by the “Optional User folder.” These new folders can have any
name and there can be one or more such folders. Please note, uncertainty
output generated by the “Uncertainty” functionality should not be saved
in the ‘Simulation Output’ folder to avoid confusion for the user (they
have the same file-type and \*.VDF extension).

**“Simulation Output” directory supplies files for multiple starting
points**

User files are now written into two user specific folders, “Simulation
Output” and “Uncertainty Output”. This directory structure separates
User files from C-ROADS-CP related files to help ensure program
integrity.

Simulation Output Directory (Folder)– This is the default location to
which files are saved whenever you save a simulation run. It is also the
default location from which files are read when you select Update run,
Load stored settings or Review run.

If you wish you may create additional sub-directories for storing
specific project output from simulation runs (e.g., “Optional User
Folder” as shown above in the figure).

Within the “Simulation Output” directory there is a sub-directory called
“Provided output.” It contains three settings files: Kyoto 110208CP.cin,
Confirmed reductions 110208CP.cin, and Potential reductions 110208CP.cin
and two simulation output files, Confirmed reductions 110208CP.vdf, and
Potential reductions 110208CP.vdf. These settings files were generated
using the A1FI reference scenario. The settings are further detailed on
the Climate Scoreboard pages of the Climate Interactive website at
http://www.climateinteractive.org/scoreboard/scoreboard-science-and-data/current-climate-proposals-1
and in related pages accessed by the navigation pane on the right hand
side of the web page. Confirmed proposals include official government
statements, adopted legislation, and UNFCC submissions. Potential
proposals include conditional proposals, legislation under
consideration, and unofficial government statements.

The analysis processes for Contribution analysis or Uncertainty analysis
also use the “Simulation Output” directory as the default for loading
saved output for analysis, but can open files from other directories
also.

**“Uncertainty Output” directory**

After you have performed an Uncertainty analysis of a simulation output,
you may save the result. C-ROADS-CP will suggest a filename that is a
concatenation of the Simulation output filename and the Analysis Control
File name which is decent way to keep track of how the file was created.
If files get confused, it is easy to recreate an analysis from the
original simulation as needed.

When you save output from an Uncertainty analysis it is always saved
into the directory, “Uncertainty Output”, regardless of whether you
navigate away from this directory during the Save File dialog
interaction. Once files have been saved, you may move them into your
Optional sub-directories and review them later from within those
sub-directories.

Our goal here is to keep Simulation Output files separate from
Uncertainty Output files. Both have the same file type suffix, .vdf, but
they are not inter-convertible.

**Reference Scenario default changed to SRES A1FI MINICAM**

The default Reference scenario has been changed to SRES A1FI MINCAM. The
previous default reference scenario will remain in the list of available
references scenarios. `A detailed explanation is available for
download <http://www.climateinteractive.org/wp-content/uploads/2014/01/Ref_Scenario_Default_v5.doc>`__.

**Web links to C-ROADS-CP information**

We have added active links within the C-ROADS-CP interface to web-based
files containing relevant information relative to simulator functions.

+---------------------------------+-----------------------------------+
| **Information**                 | **Active link location?**         |
+=================================+===================================+
| Release notes                   | Click version number on the       |
|                                 | Welcome page                      |
+---------------------------------+-----------------------------------+
| Default Reference Scenario      | Button in Help? for Ref Scenario  |
|                                 | selection                         |
+---------------------------------+-----------------------------------+
| How-to videos                   | Buttons on Getting started pages  |
+---------------------------------+-----------------------------------+
| How-to videos                   | Buttons on Reference page         |
+---------------------------------+-----------------------------------+
| C-ROADS-CP Reference guide      | Button and link on Reference      |
|                                 | page                              |
+---------------------------------+-----------------------------------+
| C-ROADS-CP Scientific review    | Button and link on Reference      |
|                                 | page                              |
+---------------------------------+-----------------------------------+
| FAQ for C-ROADS and C-ROADS-CP  | Buttons and links on FAQ page     |
+---------------------------------+-----------------------------------+

**Known Issue with Unicode in Folder/Directory Names**

While we have improved the model in numerous ways and fixed many bugs,
there is still an unresolved issue. If non-English characters are used
in the pathname of the C-ROADS-CP model folder (e.g., é, ñ, ø, î, å,
etc.), the directory path name cannot be interpreted correctly by the
modeling software and C-ROADS-CP won’t run.

We have the following two workarounds for the problem. Either rename all
the folders in the directory path name so they contain only standard
English characters so “Léo” would become Leo or Piñon would become
Pinon. Alternatively, install C-ROADS-CP in the location, C:C-ROADS-CP
v2 (that is, directly at the root of the hard drive). By avoiding
non-English characters, the supporting software will operate properly.
We apologize for this inconvenience that is out of our control. The
underlying problem will be corrected before the next C-ROADS-CP release.

**Bug and feature fixes in this version**

Some reference scenario graph lines were incorrectly labeled as to the
reference scenario source from which they were derived. Whenever a new
reference scenario was used to create a new run and this was followed by
update run or review run, the reference scenario was not the correct
reference scenario to match the updated or reviewed run, but was from
the reference scenario from the previous Create new run.

Review run, Contribution Analysis, and Uncertainty analysis now generate
a reference run when invoked. Review run determines the relevant
reference scenario that was used to produce the run being examined and
regenerates the reference scenario. Contribution Analysis and
Uncertainty analysis generate a reference run based on the current
selection for Reference Scenario on the Welcome screen.

Some minor adjustments to GDP projections to reflect better the
individual countries’ rates.

Changing to a new Reference Scenario on the Main/Welcome screen and
proceeding directly to Contribution Analysis or Uncertainty analysis did
not generate a new Reference run (ref.vdf) which would incorporate the
new reference scenario settings. This has been corrected. A copy of
ref.vdf is now placed into the Simulation Output directory each time a
new reference scenario is generated so ref.vdf represents the active
Reference Scenario

**14 Dec 10**

**v2.142**

We have added two new graph types that allow comparisons of runs from
individual countries. The graphs are entitled “Comparative FF CO2
emissions by country” and “CO2 equivalent non-forest emissions by
country group” and are found in the left graph display pane. Access to
them is from the “CO2 Emissions” and “CO2 Equiv” drop-down menus. The
new graphs are at the bottom of each drop-down list and labeled
“Comparative FF CO2 emissions by country” and “Comparative CO2e
emissions by country”, respectively.

For this new graph to be convenient, you need to show only one or at
most two countries at a time. This can be accomplished in several ways.
On the Welcome/main screen you may click the “Set graph defaults” button
and set the default to the one or two countries that you wish to view –
this setting changes the simulation default until you change it again.

You could also perform a “one-session” re-set in the control panel
screen using the “Select regions” button; this changes the settings
during the current simulation session only and then reverts to the
defaults when you “Return to main” and cycle through the welcome/main
screen.

The most temporary method for controlling what lines display on a graph
is to check and un-check the graph legend check boxes. This is temporary
– even switching between graphs reverts to the default. Note that if you
use the “Data table” or “Export Image/data” buttons, these will export
all the data represented in the graph legend, whether the check boxes
are checked or not.

There is a maximum of 12 runs before we run out of name space.

In the above screen shot, with the legends showing India and US for 3
conditions, “current_run” is shown because “Create new run” was used to
enter the control panel, and current_run is always shown in this mode.
To omit the current run, you would enter the control panel from the
welcome/main screen using the “Review runs” button selecting one of the
runs you wish to review, and then using the Load/unload run button in
the control panel to build up the set you wish.

The name of the file from which the data set is derived is appended to
the country name in [square brackets], so careful naming or renaming of
your saved data sets will create a more informative legend.

We have also corrected a bug which prevented the scroll bars from
appearing on the table entry for 15 region land use and FF emissions, as
well as one that affected forestry inputs in 6 region mode.

For new users, there is now a link to each of the tutorial videos from
the “Getting started” page and the “Getting started” quick guide.
Clicking the button opens your web browser to the link containing the
video.

**3 Dec 10**

The update includes significant new capabilities, as well as
improvements to make it easier to use.

There are 5 changes and additions that you’ll find at the interface
level that are new or improved. There are also improvements in the
underlying simulation program.

-  At the opening “Welcome” screen you may choose from a collection of
   Reference scenarios, derived from EMF22 and SRES, and you may also
   specify your own user-defined reference scenario. When you choose
   “Create new run”, your chosen Ref scenario is used. The footer in the
   graphs will reflect the name of the Reference scenario, as will the
   legend in comparative graphs. There is also a reminder on the Control
   panel page so you can easily see the active reference scenario.

-  Additionally, on the Welcome screen you’ll see two new buttons,
   “Contribution analysis” and “Uncertainty analysis”:

   -  Contribution analysis takes a previously saved C-ROADS-CP run and
	  performs a leave-one-out analysis of the global data to determine
	  the contributions of each country/region to CO2 ppm, Temperature
	  and Radiative Forcing.

   -  Uncertainty takes a previously saved run and performs an
	  uncertainty/sensitivity analysis using an analysis toolset file
	  and displays the results for multiple variables – see the Help?
	  screen.

-  On the main Control screen, under the tab for Fossil Fuel CO2
   emissions, you will find that the input controls now allow a new
   entry mode for each country/region, by Carbon Intensity. This adds to
   the previously available input modes, “Reference year” and “Reference
   scenario.” Finally, the OFF mode cleans up the Fossil Fuel CO2
   emissions input interface when it is not in use. The “Target” boxes
   may be used in any order, and their order of use is controlled by the
   setting of the target year.

-  When you select the Land use emissions tab, you’ll find that you may
   enter these globally, as before, or by country/region. There is a
   table mode for the country/region entry that allows for easy review
   of the settings or for easy entry for multiple country/regions.

The program will install in a folder, C-ROADS-CP v2, and so will not
overwrite your previous version of C-ROADS from last year.

.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image003.png| image:: media/image1.png
   :width: 4in
   :height: 2.87222in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image005.png| image:: media/image2.png
   :width: 2.40417in
   :height: 1.96806in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image007.png| image:: media/image3.png
   :width: 4.23403in
   :height: 1.05347in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image009.png| image:: media/image4.png
   :width: 11.82986in
   :height: 3.10625in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image011.png| image:: media/image5.png
   :width: 3.88264in
   :height: 2.76597in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image013.png| image:: media/image6.png
   :width: 2.77639in
   :height: 2.44653in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/image015.png| image:: media/image7.png
   :width: 13.14861in
   :height: 3.30833in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/clip_image004.png| image:: media/image8.png
   :width: 3.08542in
   :height: 0.98958in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/clip_image006.png| image:: media/image9.png
   :width: 1.94653in
   :height: 2.41458in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/clip_image008.png| image:: media/image10.png
   :width: 2.76597in
   :height: 0.75556in
.. |Design Changes to Main - Welcome Screen| image:: media/image11.png
   :width: 6.69167in
   :height: 1.48958in
.. |/var/folders/tg/1k2c7tts0z73mx2dszj1s2mw0000gn/T/com.microsoft.Word/WebArchiveCopyPasteTempFiles/directory-structure.png| image:: media/image12.png
   :width: 2.46806in
   :height: 2.19167in
