# RawResManager

**Namespace:** `Torappu.Resource`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Resource
public class RawResManager : IHotfixable
{
	public const String AB_DIR_NAME; // 0x0
	public const String AB_DIR_PREFIX; // 0x0
	public const String TAG_FILE_NAME; // 0x0
	private static ILocalResourceEvents s_localResEvent; // 0x0
	private static __XLua_Gen_Delegate149 __Hotfix0_get_ROOT_DIR_PATH; // 0x8
	private static __XLua_Gen_Delegate89 __Hotfix0_GetABFullPath; // 0x10
	private static __XLua_Gen_Delegate8 __Hotfix0_CheckExist; // 0x18
	private static __XLua_Gen_Delegate8 __Hotfix0_EditorOnlyCheckExistWithFullPath; // 0x20
	private static __XLua_Gen_Delegate89 __Hotfix0_EditorOnlyGetAssetPath; // 0x28
	private static __XLua_Gen_Delegate1 __Hotfix0__OnAssetExists; // 0x30
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x38

	public static String ROOT_DIR_PATH { get; }

	// RVA: 0x67981a0 VA: 0x7598db01a0
	public static String get_ROOT_DIR_PATH() { }
	// RVA: 0x679821c VA: 0x7598db021c
	public static String GetABFullPath(String resPathWithExtension) { }
	// RVA: 0x679837c VA: 0x7598db037c
	public static Boolean CheckExist(String resPathWithExtension) { }
	// RVA: 0x679854c VA: 0x7598db054c
	public static Boolean EditorOnlyCheckExistWithFullPath(String resFullPathWithExtension) { }
	// RVA: 0x67985bc VA: 0x7598db05bc
	public static String EditorOnlyGetAssetPath(String resPathWithExt) { }
	// RVA: 0x67984e0 VA: 0x7598db04e0
	private static Void _OnAssetExists(String resPathWithExtension) { }
	// RVA: 0x6798648 VA: 0x7598db0648
	public Void .ctor() { }
}
```