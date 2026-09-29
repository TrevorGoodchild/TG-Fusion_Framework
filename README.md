TG Fusion Macro Framework


PURPOSE
Central development and reference environment for reusable DaVinci Resolve / Fusion macros.


MASTER SOURCE
Google Drive is the authoritative source for this framework. Project uploads or local copies are secondary references only.


CENTRAL FILES
01_Registry/TG_Fusion_Macro_Registry — authoritative macro registry.
01_Registry/TG_Expression_Library — authoritative reusable expression library.
00_Framework/TG_Naming_Convention — authoritative naming and architecture rules.
02_References/setting_references — tested Fusion .setting references.
03_Macros — generated macro files organized by type code.
99_Archive — deprecated or superseded files.


DEVELOPMENT WORKFLOW
1. Read the Macro Registry.
2. Read the Naming Convention.
3. Check the Expression Library.
4. Check relevant verified .setting references.
5. Define purpose and type code.
6. Determine version.
7. Plan native Fusion node structure.
8. Plan CTRL and Inspector structure.
9. Plan comp/aspect-ratio behavior.
10. For non-BG macros use a transparent full-comp canvas.
11. For AR macros plan multiple external inputs and transform/distribution only.
12. Plan animation controls where appropriate.
13. Build the macro.
14. Check Fusion syntax and connections.
15. Test in DaVinci Resolve / Fusion.
16. Correct errors with minimal structural change.
17. Update the Macro Registry.
18. Add genuinely reusable expressions to the Expression Library.


VERIFICATION POLICY
A .setting reference is not considered verified merely because it was generated. It becomes a Golden Reference only after successful testing in DaVinci Resolve / Fusion. Known working structures should be reused instead of rebuilt unnecessarily.


REGISTRY POLICY
Every macro creation, modification, bug fix, version change or status change must be reflected in TG_Fusion_Macro_Registry. The registry remains empty of speculative production macros until explicitly requested.


EXPRESSION POLICY
Before inventing a reusable expression, check TG_Expression_Library. Add an expression only when it has general reuse value. Do not mark it verified until tested in Fusion.