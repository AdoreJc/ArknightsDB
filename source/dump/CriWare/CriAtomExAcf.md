# CriAtomExAcf

**Namespace:** `CriWare`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExAcf
{


	// RVA: 0x41263d4 VA: 0x759673e3d4
	public static Int32 GetNumAisacControls() { }
	// RVA: 0x4126440 VA: 0x759673e440
	public static Boolean GetAisacControlInfo(UInt16 index, out AisacControlInfo info) { }
	// RVA: 0x41266dc VA: 0x759673e6dc
	public static Int32 GetNumDspSettings() { }
	// RVA: 0x4126748 VA: 0x759673e748
	public static Int32 GetNumDspSettings(IntPtr acfData, Int32 size) { }
	// RVA: 0x41267d0 VA: 0x759673e7d0
	public static String GetDspSettingNameByIndex(UInt16 index) { }
	// RVA: 0x41268ec VA: 0x759673e8ec
	public static String GetDspSettingNameByIndex(IntPtr acfData, Int32 size, UInt16 index) { }
	// RVA: 0x4126a3c VA: 0x759673ea3c
	public static Boolean GetDspSettingInformation(String name, out AcfDspSettingInfo info) { }
	// RVA: 0x4127140 VA: 0x759673f140
	public static Boolean GetDspSettingSnapshotInformation(UInt16 index, out AcfDspSettingSnapshotInfo info) { }
	// RVA: 0x4127860 VA: 0x759673f860
	public static Boolean GetDspBusInformation(UInt16 index, out AcfDspBusInfo info) { }
	// RVA: 0x412794c VA: 0x759673f94c
	public static Boolean GetDspBusLinkInformation(UInt16 index, out AcfDspBusLinkInfo info) { }
	// RVA: 0x4127d6c VA: 0x759673fd6c
	public static Int32 GetNumCategories() { }
	// RVA: 0x4127dd8 VA: 0x759673fdd8
	public static Int32 GetNumCategoriesPerPlayback() { }
	// RVA: 0x4127e44 VA: 0x759673fe44
	public static Boolean GetCategoryInfoByIndex(UInt16 index, out CategoryInfo info) { }
	// RVA: 0x4128280 VA: 0x7596740280
	public static Boolean GetCategoryInfoByName(String name, out CategoryInfo info) { }
	// RVA: 0x412853c VA: 0x759674053c
	public static Boolean GetCategoryInfoById(UInt32 id, out CategoryInfo info) { }
	// RVA: 0x41287e4 VA: 0x75967407e4
	public static Int32 GetNumGlobalAisacs() { }
	// RVA: 0x4128850 VA: 0x7596740850
	public static Boolean GetGlobalAisacInfoByIndex(UInt16 index, out GlobalAisacInfo info) { }
	// RVA: 0x4128e2c VA: 0x7596740e2c
	public static Boolean GetGlobalAisacInfoByName(String name, out GlobalAisacInfo info) { }
	// RVA: 0x41290e8 VA: 0x75967410e8
	public static Boolean GetGlobalAisacGraphInfo(GlobalAisacInfo aisacInfo, UInt16 graphIndex, out AisacGraphInfo graphInfo) { }
	// RVA: 0x41295d0 VA: 0x75967415d0
	public static Boolean GetGlobalAisacValue(GlobalAisacInfo aisacInfo, Single control, AisacGraphType type, out Single value) { }
	// RVA: 0x41297cc VA: 0x75967417cc
	public static Boolean GetAcfInfo(out AcfInfo acfInfo) { }
	// RVA: 0x4129ea4 VA: 0x7596741ea4
	public static Int32 GetNumSelectors() { }
	// RVA: 0x4129f10 VA: 0x7596741f10
	public static Boolean GetSelectorInfoByIndex(UInt16 index, out SelectorInfo info) { }
	// RVA: 0x412a328 VA: 0x7596742328
	public static Boolean GetSelectorInfoByName(String name, out SelectorInfo info) { }
	// RVA: 0x412a5d8 VA: 0x75967425d8
	public static Boolean GetSelectorLabelInfo(SelectorInfo selectorInfo, UInt16 labelIndex, out SelectorLabelInfo info) { }
	// RVA: 0x412ab08 VA: 0x7596742b08
	public static Int32 GetNumBuses() { }
	// RVA: 0x412ab74 VA: 0x7596742b74
	public static Int32 GetMaxBusesOfDspBusSettings() { }
	// RVA: 0x412abe0 VA: 0x7596742be0
	public static String FindBusName(String busName) { }
	// RVA: 0x412ac88 VA: 0x7596742c88
	public static CriAtomExOutputPort GetOutputPort(String name) { }
	// RVA: 0x41263d8 VA: 0x759673e3d8
	private static extern Int32 criAtomExAcf_GetNumAisacControls() { }
	// RVA: 0x4126650 VA: 0x759673e650
	private static extern Boolean criAtomExAcf_GetAisacControlInfo(UInt16 index, IntPtr info) { }
	// RVA: 0x412ad90 VA: 0x7596742d90
	private static extern UInt32 criAtomExAcf_GetAisacControlIdByName(String name) { }
	// RVA: 0x412ae24 VA: 0x7596742e24
	private static extern String criAtomExAcf_GetAisacControlNameById(UInt32 id) { }
	// RVA: 0x41266e0 VA: 0x759673e6e0
	private static extern Int32 criAtomExAcf_GetNumDspSettings() { }
	// RVA: 0x412674c VA: 0x759673e74c
	private static extern Int32 criAtomExAcf_GetNumDspSettingsFromAcfData(IntPtr acf_data, Int32 acf_data_size) { }
	// RVA: 0x4126870 VA: 0x759673e870
	private static extern IntPtr criAtomExAcf_GetDspSettingNameByIndex(UInt16 index) { }
	// RVA: 0x41269a8 VA: 0x759673e9a8
	private static extern IntPtr criAtomExAcf_GetDspSettingNameByIndexFromAcfData(IntPtr acf_data, Int32 acf_data_size, UInt16 index) { }
	// RVA: 0x4126c5c VA: 0x759673ec5c
	private static extern Boolean criAtomExAcf_GetDspSettingInformation(String name, IntPtr info) { }
	// RVA: 0x4127360 VA: 0x759673f360
	private static extern Boolean criAtomExAcf_GetDspSettingSnapshotInformation(UInt16 index, IntPtr info) { }
	// RVA: 0x4127864 VA: 0x759673f864
	private static extern Boolean criAtomExAcf_GetDspBusInformation(UInt16 index, out AcfDspBusInfo info) { }
	// RVA: 0x412aeb8 VA: 0x7596742eb8
	private static extern Int32 criAtomExAcf_GetDspFxType(UInt16 index) { }
	// RVA: 0x412af34 VA: 0x7596742f34
	private static extern String criAtomExAcf_GetDspFxName(UInt16 index) { }
	// RVA: 0x412afc8 VA: 0x7596742fc8
	private static extern Boolean criAtomExAcf_GetDspFxParameters(UInt16 index, IntPtr parameters, Int32 size) { }
	// RVA: 0x4127b5c VA: 0x759673fb5c
	private static extern Boolean criAtomExAcf_GetDspBusLinkInformation(UInt16 index, IntPtr info) { }
	// RVA: 0x412b064 VA: 0x7596743064
	private static extern Int32 criAtomExAcf_GetNumCategoriesFromAcfData(IntPtr acf_data, Int32 acf_data_size) { }
	// RVA: 0x4127d70 VA: 0x759673fd70
	private static extern Int32 criAtomExAcf_GetNumCategories() { }
	// RVA: 0x412b0e8 VA: 0x75967430e8
	private static extern Int32 criAtomExAcf_GetNumCategoriesPerPlaybackFromAcfData(IntPtr acf_data, Int32 acf_data_size) { }
	// RVA: 0x4127ddc VA: 0x759673fddc
	private static extern Int32 criAtomExAcf_GetNumCategoriesPerPlayback() { }
	// RVA: 0x4128060 VA: 0x7596740060
	private static extern Boolean criAtomExAcf_GetCategoryInfo(UInt16 index, IntPtr info) { }
	// RVA: 0x412849c VA: 0x759674049c
	private static extern Boolean criAtomExAcf_GetCategoryInfoByName(String name, IntPtr info) { }
	// RVA: 0x4128758 VA: 0x7596740758
	private static extern Boolean criAtomExAcf_GetCategoryInfoById(UInt32 id, IntPtr info) { }
	// RVA: 0x41287e8 VA: 0x75967407e8
	private static extern Int32 criAtomExAcf_GetNumGlobalAisacs() { }
	// RVA: 0x4128a6c VA: 0x7596740a6c
	private static extern Boolean criAtomExAcf_GetGlobalAisacInfo(UInt16 index, IntPtr info) { }
	// RVA: 0x4129048 VA: 0x7596741048
	private static extern Boolean criAtomExAcf_GetGlobalAisacInfoByName(String name, IntPtr info) { }
	// RVA: 0x41293ec VA: 0x75967413ec
	private static extern Boolean criAtomExAcf_GetGlobalAisacGraphInfo(IntPtr aisac_info, UInt16 graph_index, IntPtr graph_info) { }
	// RVA: 0x4129720 VA: 0x7596741720
	private static extern Boolean criAtomExAcf_GetGlobalAisacValue(IntPtr aisac_info, Single control, AisacGraphType type, out Single value) { }
	// RVA: 0x41299e0 VA: 0x75967419e0
	private static extern Boolean criAtomExAcf_GetAcfInfo(IntPtr acf_info) { }
	// RVA: 0x412b16c VA: 0x759674316c
	private static extern Boolean criAtomExAcf_GetAcfInfoFromAcfData(IntPtr acf_data, Int32 acf_data_size, IntPtr acf_info) { }
	// RVA: 0x4129ea8 VA: 0x7596741ea8
	private static extern Int32 criAtomExAcf_GetNumSelectors() { }
	// RVA: 0x412a120 VA: 0x7596742120
	private static extern Boolean criAtomExAcf_GetSelectorInfoByIndex(UInt16 index, IntPtr info) { }
	// RVA: 0x412a538 VA: 0x7596742538
	private static extern Boolean criAtomExAcf_GetSelectorInfoByName(String name, IntPtr info) { }
	// RVA: 0x412a8dc VA: 0x75967428dc
	private static extern Boolean criAtomExAcf_GetSelectorLabelInfo(IntPtr selector_info, UInt16 label_index, IntPtr info) { }
	// RVA: 0x412b208 VA: 0x7596743208
	private static extern Int32 criAtomExAcf_GetNumBusesFromAcfData(IntPtr acf_data, Int32 acf_data_size) { }
	// RVA: 0x412ab0c VA: 0x7596742b0c
	private static extern Int32 criAtomExAcf_GetNumBuses() { }
	// RVA: 0x412b28c VA: 0x759674328c
	private static extern Int32 criAtomExAcf_GetMaxBusesOfDspBusSettingsFromAcfData(IntPtr acf_data, Int32 acf_data_size) { }
	// RVA: 0x412ab78 VA: 0x7596742b78
	private static extern Int32 criAtomExAcf_GetMaxBusesOfDspBusSettings() { }
	// RVA: 0x412abe4 VA: 0x7596742be4
	private static extern String criAtomExAcf_FindBusName(String bus_name) { }
	// RVA: 0x412acfc VA: 0x7596742cfc
	private static extern IntPtr criAtomExAcf_GetOutputPortHnByName(String name) { }
	// RVA: 0x412b310 VA: 0x7596743310
	public Void .ctor() { }
}
```