<h1>Altium Designer addons   </h1>
This project contains set of scripts, examples and other content which is developed to provide extended features for Altium Designer  unified design environment for electronics development.<br>
The project is in Czech and English language. Updates are listed <a href='http://code.google.com/p/altium-designer-addons/updates/list'>here</a>. <br>
Distributed "as is" with no warranty. In case of difficulties please contact leaders of this project (contacts are at the left sidebar <=) or create a record in Issues part of this page.<br>
Altium Script Gallery was moved to <a href='http://wiki.altium.com'>Altium Wiki</a>. You can find it and download on <a href='http://wiki.altium.com/display/ADOH/Download+Examples+and+Reference+Designs'>Examples and Reference Designs page</a>.<br>
<br><br>
<b>Contributors</b> (sorted chronologically): Petr Tosovsky, Petar Perisin, John Go-Soco, Mattias Ericson, Darren Moore, Colby Meyer, Juan Martinez, Rob Sterling, Jeff Collins, Ran Shahar, Tony Chilco, Ryan Rutledge, Erick Albach, Matija Markovic, Cyril Andreatta, Randy Clemmons, Miklós Zsikla<br>
<br><br>
<br>
<br>
<hr><br>
<br>
<br>
Google Code service is not supporting sharing files via Downloads section. This section was removed in this project and it is replaced by shared Google Drive folder as easiest solution of the situation. All content of Altium Designer Addons can be found there or you can use checkout via Subversion/SVN client (details on Source tab).<br>
<h1><a href='https://drive.google.com/folderview?id=0B9wYgjewDMDFYzBTU1pMR0xaSHM&usp=sharing#list'>Download</a></h1>
<br>
<br>
<hr><br>
<br>
<br>
<b>If you are interested to be committer, please send an email to retry.var (a) gmail.com. It is needed to have Google account (gmail) to access Google Code where Altium Addons is hosted.</b><br>
You can read more about commiting your content here <a href='AltiumAddonsCommitersRecomendation.md'>AltiumAddonsCommitersRecomendation</a>
<br>
<br>
<hr><br>
<br>
<br>
<h2>Altium Designer LIBRARIES available at Addons page:</h2>
<ul><li><b>Libs_NetTieLib</b> - set of components for joining and splitting signals on PCB. Details here <a href='NetTieLib.md'>NetTieLib</a>
</li><li><b>Libs_CAndreatta</b> - set of individual schematic symbols and footprints Cyril Andreatta. Plain SchLib and PcbLib files. Details here <a href='Libs_CAndreatta.md'>Libs_CAndreatta</a>
</li><li><b>Libs_RRutledge</b> - General Library by Ryan Rutledge. Plain SchLib and PcbLib files. Details here <a href='Libs_RRutledge.md'>Libs_RRutledge</a></li></ul>

<b>Thank you Ryan for this kick off in the Libraries section.</b>

<h2>Altium Designer templates available at Addons page:</h2>
<ul><li><b>AltiumPCBProjectTemplate</b> - Sample project template for 2 and 4 layer board design in Altium Designer. Details can be found here <a href='AltiumPCBProjectTemplate.md'>AltiumPCBProjectTemplate</a></li></ul>

<h2>Scripts available at our Addons page:</h2>
<ul>
<li><b>OpenComponentPCBLib</b> script - opens the component footprint library of a selected component on PCB<br>
<li><b>BoardAutoSizer</b> script - Redefine Board Shape based on Embedded Board Arrays<br>
<li><b>Fix Connections</b> script - Fix Connections is a modified version of Fix Overlaps v2.2 created by Petar Perisin, there are some features and UI improvements for better usability.<br>
<li><b>Via Soldermask Barrel Relief</b> script - the script searches for vias on board with higher then defined hole size and opens soldermask for the vias by given value from the edge of hole to prevent possible mask damage.<br>
<li><b>Calculator for converting units</b> <a href='mil_mm_conv.md'>mil_mm_conv</a> script - script allows easily convert entered value to all other units interpretations<br>
<li><b>ShowHideDesignators</b> script - script allows easily show or hide Designators and Comments in PcbDoc file<br>
<li><b>RotationStep-Toggle-Modify</b> script - easier way to modify PCB editor rotation step settings (when Spacebar is used to rotate an object)<br>
<li><b>AutoHotkey Enhancement</b> script - script provides several enhancements to Altium Designer, such as limited autocomplete for filter expressions, improved mouse wheel support, and various tweaks to save time on frequently-used tasks<br>
<li><b>Distribute</b> script - script that distributes distance between selected lines.<br>
<li><b>Run_exe</b> script - script that can open exe file from Altium. Currently supports PCB Toolkit, TraceSim and TX-Line.<br>
<li><b>FilletWithRadius</b> script - script that rounds connection on horizontaland vertical lines by fixed radius value.<br>
<li><b>Arc8</b> script - script that connects arc tangent and via/Pad, or places tangent to connect two arcs.<br>
<li><b>FixOverlaps</b> script - script that will clean nets in chosen net class of overlaps.<br>
<li><b>OpenSchDocs</b> script - script will open all sch documents in current PCB project.<br>
<li><b>UpdateNetOnclick</b> script - script will update net of all selected objects to a net user chooses with a mouse click.<br>
<li><b>LengthTuningHelper</b> script - script that helps in length tuning of DDR3-FPGA interfaces, where you need to include length of lines inside FPGA. This one also helps in length tuning when you need to include via stack size to length of a net.<br>
<li><b>LayerStackExporter</b> script - script that exports layer stack to a CSV file.<br>
<li><b>UpdateFootprintHeightFrom3dModelHeight</b> script - script that updates Footprint height based on height of it's 3D model (in PCB library).<br>
<li><b>SelectViaAntennas</b> script - This script selects unnecessary vias on PCB (vias connected only on one layer).<br>
<li><b>ReAnnotateSelection</b> script - This can be used to re-annotate selected components on PCB.<br>
<li><b>ZoomAndCenter</b> script - This script invokes zoom and centers view on zoomed area. similar how PCAD worked with zoom.<br>
<li><b>PlaceRectangle</b> script - This script places a rectangle on the PCB.<br>
<li><b>AutoRouter_Interface</b> script - This script creates an interface to auto routers. It fixes some problems with rte importer and dsn exporter, and gives user the ability to import ses file.<br>
<li><b>CalculateCopperArea</b> script - This script calculates area of selected poly or region.<br>
<li><b>LayersAndObjects</b> script - This script creates a form similar to a panel, from which you can control layer and object display. Originated from LayersPanel script.<br>
<li><b>SelectBadConnections</b> script - This script checks weather Tracks and arcs on signal connect totaly on some other object. Center-to-center check is done. If not, it is selected. Tolerance (and zero tolerance) is supported.<br>
<li><b>WheelSelector</b> script - This script allows selection and scrolling through insight form using wheel.<br>
<li><b>AddDatumPointsToArcs</b> script - This script will add tracks to selected arcs. This tracks end in arc center, so after that you can easily move objects to arc center.<br>
<li><b>AutoSTEPplacer</b> script - This script will place STEP files on a footprint in a library if they have same name. STEP file must be in the same directory as library, or it's subfolder.<br>
<li><b>PCBScale</b> script - This script allows you to scale selected objects on a PCB by amount.<br>
<li><b>LayersPanel</b> script - This script creates a form similar to a panel, from which you can control layer display. Originated from ShowHideLayers script.<br>
<li><b>Man2APDesignators</b> script - This script will change manual designators to auto-positioned. Will operate on all or selected components.<br>
<li><b>ShowHideLayers</b> script - This script allows very easy turning layers on/off.<br>
<li><b>SelectConnectedOnLayer</b> script - This script is similar to SelectConnectedTracks, only it works with arcs, it's faster and objects do not have to have common point.<br>
<li><b>ComponentPlacement</b> script - This script allows user to equalize relative component placement between two groups of components.<br>
<li><b>MoveAPdesignators</b> script - This script allows user to modify distance between auto-positioned designators and component.<br>
<li><b>ParamsToPCB</b> script - This script allows user to transfer component parameters to the PCB.<br>
<li><b>CreateTableOfContents</b> script - Script that can be used to create Table Of Contents on newly created top level sheet in PCB Project.<br>
<li><b>MultiPCBProject</b> script - This Script enables Project to be used with multiple PCB documents, so that project is split among multiple PCB Documents. It is workaround solution that uses blankets to point which PCB document gets the circuit under it.<br>
<li><b>XIA_Update_From_Database</b> script -  This is the script in use by XIA LCC to update schematic designs with respect to the company components database.  This includes synchronization of user parameters (MFGNAME, Description, etc.), synchronization of footprints, and setting the Comment parameter.<br>
<li><b>XIA_Release_Manager</b> script - This is the script in use at XIA LLC to do all Altium output generation, packaging (zipping), and release-tag.  Everything is done within Subversion (SVN).<br>
<li><b>FilterObjects</b> script - Script that filters objects based on type, layer and parent.<br>
<li><b>LockNetRouting</b> script - Script which locks or unlocks routing tracks, vias and components (possible to exclude components) on selected net. That aims to prevent some unwanted changes on PCB during routing.<br>
<li><b>SingleLayerModeWithConnectionLines</b> script - This script enables user to see all connection lines in a display similar to single layer mode.<br>
<li><b>VendorTools</b> script - Script that can be used to exchange info between different FPGA vendors and AD. Currently supports Altera<br>
<li><b>ConnectionLinesOnSelection</b> script - script that enables user to show/hide connection lines on selected objects<br>
<li><b>TrimExtend</b> script - Script that trims or extends tracks up to a point where first selected track is. This function is available in all 3D tools<br>
<li><b>TestpointMaker</b> script - This script creates test points for a net class.<br>
<li><b>StitchingVias</b> script - Script that generates stitching vias on a PCB. Vias are added to graphical component for easier use.<br>
<li><b>ThievingPads</b> script - Script that adds thieving pads to a PCB Document. Pads are added in a dummy component, that allows easier manipulation<br>
<li><b>LR_Justify</b> script - Script that switches selected text between left and right justification on a sch.<br>
<li><b>AddWireStubsSch</b> script - it search for unconected pins of components in schematic sheet and draw small segment of a wire on it equipped by net label according to the name or designator of the pin<br>
<li><b>Adjust Designators 2 script</b> - This script modifies designator position. It is based on AdjustDesignator script from Mattias Ericson, only user gets the form in which he can enable/disable and modify certain options, like layers, height etc...<br>
<li><b>MechLayerNames script</b> - Script that saves mech layer names to txt file. This names can then be imported it to another PCB Document.<br>
<li><b>DeleteInvalidPCBObjects script</b> - Cleans a PCB documents of some current invalid objects. Checks for invalid regions or polygons and deletes them.<br>
<li><b>DrcOnOff script</b> - This script toggles Online DRC check box in DXP->Preferences->PCB editor->General what enables/disables online DRC checks.<br>
<li><b>LockMultiPartComponents script</b> - This script can be used to lock parts in multi-part components. It searches for "Group" parameter in all components and assigns a value in it, based on current component designator.<br>
<li><b>PrintAllvariants script</b> - This Script saves variant information to CSV file, which can then be easily opened in excel.<br>
<li><b>SheetParameters script</b> - script that modifies document parameters in all SCH documents of focused project.<br>
<li><b>FlipComponents script</b> - Script flips selected components. If there are no selected objects it asks user to click on components that will be flipped. It uses smart mechanism for flipping, which tries to keep pads position.<br>
<li><b>MoveToLayer script</b> - This script moves selected copper tracks to selected signal layer, while maintaining connectivity with Vias that are automatically placed.<br>
<li><b>IsPadCenterConnected script</b> - This script checks weather pads have track in their center. if not, pad is selected.<br>
<li><b>DesignReuse_v3.0 script</b> - Script that simplifies true design reuse - route circuit once and reuse same routing in your next design. This automated design reuse is using Device Sheets or SCH snippets in SCH, and PCB Snippets in PCB. For more info read "How to use this script.odt" document (in OpenOffice or M$ Word) form the zip file<br>
<li><b>SpiralTrackVer0<a href='1.md'>1</a>.8 script</b> - Spiral Generator script made by Darren Moore.<br>
<li><b>PlanarTXv0.7 script</b> - Script to create planar transformer made by Darren Moore.<br>
<li><b>Fillet script</b> - Script that places arcs to corners of selected tracks (Fillet command).<br>
<li><b>DeleteSelectedSplit script</b> - Script that can be used to delete selected split plane. It actually creates region based on selected split plane, with holes inside, so no copper will appear on that place.<br>
<li><b>DeleteAllSelectedItemsInPCBLIB script</b> - This script can be used to delete selected objects in PCB Library. Currently you can only delete selected objects that are part of currently visible footprint, but this script deletes selected objects that are in other footprints.<br>
<li><b>FormatPaintBrush script</b> - This script is used to copy formattings from one object to the others. Currently it works on dimensions, coordinate, String and poly in PCB and all sch objects.<br>
<li><b>Current Calculator script</b> - PCB script that gives the user a dialog box with current (Amperes) handling calculations for a selected track. The script determines if the track is on an internal or external layer, and provides current calculations for 1, 5, and 10°C rise above ambient.<br>
<li><b>Hyperlynx Exporter script</b> - Script for PCB export to hyp file. It adds fills, regions, polygons and split planes in hyp file.<br>
<li><b>RenumberPads script</b> - Script helps with changing order of pads mainly in Altium PCBLIBs. You just start script, select start index and increment and you create new designators of pads by clicking on them in the new order.<br>
<li><b>RoomFromPoly script</b> - Script to create room from selected objects or from selected polygon.<br>
<li><b>AdjustDesignators script</b> - it will center the designator in top and bottom overlay.<br>
<li><b>ZoomComponent script</b> - PCB function similar to Altium's Jump Component, but it also zoom, mask and/or select component.<br>
<li><b>SCHSelectionFilter script</b> - Script that uses select Touching trectangle, but user can choose object types that will be selected.<br>
<li><b>SCH-SelectTouchingRectangle script</b> - Script made because some people wanted select touching rectangle feature in Sch.<br>
<li><b>IncrementingDesignators script</b> - Script that enables user to set designators with mouse. Works on Components (in SchDoc and PCBDoc), pins (SCHLIB) and pads (PCBLIB). Designators can be swapped too. When working with pins it can also move pin names.<br>
<li><b>IBIS Editor script</b> - Script that overrides <a href='Model.md'>Selector</a> and <a href='Submodel.md'>Submodel</a> keywords in IBIS File.<br>
<li><b>EagleToAD conversion package</b> - package of scripts for conversion of PCB project from Cadsoft Eagle to Altium Designer (manual available only in Czech)<br>
<li><b>CopyAngleToComponent script</b> - script for copying angle of track to a component<br>
<li><b>SelectConnectedTrack script</b> - script for selection of connected NoNet track on Mech layers<br>
<li><b>Custom Pick&Place report script</b> - script for generating user defined P&P for SMD components only<br>
<br>
<br>
<br>
<img src='http://altium-designer-addons.googlecode.com/svn/trunk/SelectConnectedTrack/Select%20Connected%20Track.png' />

SelectConnectedTrack script result screenshot