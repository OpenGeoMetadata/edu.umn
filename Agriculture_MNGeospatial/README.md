|    Collection Details          |                                          |
|--------------------------------|------------------------------------------| 
| Name                           | Agriculture & Farming: Minnesota Geospatial Commons             |
| Point of Contact               | Karen Majewicz                              |
| Base URL                       | http://gisdata.mn.gov                    |
| \# of records total (estimate) | 12                               |
| Stage 1 metadata standard      | Minnesota Geographic Metadata Guidelines |

Downloaded from http://54.173.174.15:8080/opengeoportal/

## Stage 1
This stage covers the initial capture of collection metadata files, in whatever metadata standard/format they currently exist in. These "raw" records should be placed into the `stage1`, likely as XML files.

## Stage 2
At this stage, UMN will transform the input files from Stage 1 using semi-automated methods (XSLTs and other scripting). The transformed outputs will be placed in the `stage2` folder, as ISO 19139 (ArcGIS?) formatted XMLs.

## Stage 3
Your institution will take the outputs from `stage2` and manually finish the creation of the metadata records. If using the ArcGIS Online metadata editing workflow we went over at the Summit, the files placed here will be those downloaded when you clicked `Save Local Copy` in the metadata editor. These will be in the Esri metadata format, but if you prefer another workflow/toolset, that's fine as long as you end up with a "complete" XML record saved in the `stage3` folder.

## Stage 4
This is where UMN will place the final ISO 19139 compliant XML files. At this point a visual review and double checking the records by multiple parties is advisable, to catch any transormation errors or omissions that made it through to the end.

### Hints, tricks, and tips
- Keep the file names the same across the stages. For example, a file named `dnr_water_hydrography.xml` in `stage1` should be named `dnr_water_hydrography.xml` in `stage2`, and `dnr_water_hydrography.xml` in `stage 3`, and `dnr_water_hydrography.xml` in `stage4`.
- GitHub lets you look at different versions of the files, meaning as long as you commit (kind of like saving) your work somewhat frequently, you'll have left a very useful trail of breadcrumbs to find your way back if needed.
- Each Collection folder has a corresponding GitHub Issue in your repository. If you have any problems or anything you'd like to report, that's a good spot for it. Your comment will sync to the appropriate Asana project task.
