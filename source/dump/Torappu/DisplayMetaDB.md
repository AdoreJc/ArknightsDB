# DisplayMetaDB

**Namespace:** `Torappu`


## Methods

- `HomeBackgroundSingleData GetHomeBgDataById(String)`

- `HomeThemeDisplayData GetHomeThemeDataById(String)`

- `String GetHomeBgDefaultMusicId()`

- `PlayerAvatarPerData GetAvatarDataById(String)`

- `Boolean TryGetAvatarDataById(String, out)`

- `PlayerAvatarGroupData GetAvatarGroupDataByType(PlayerAvatarGroupType)`

- `NameCardV2ModuleData GetNameCardFixedModuleDataById(String)`

- `NameCardV2RemovableModuleData GetNameCardRemovableModuleDataById(String)`

- `NameCardV2SkinData GetNameCardSkinDataById(String)`

- `Void _InitVariantDict()`

- `Boolean StoryVariantExist(String, out)`

- `String GetStoryVariantId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DisplayMetaDB : ConstTable`2
{
	private Dictionary`2 m_avatarDataMap; // 0x60
	private Dictionary`2 m_avatarGroupMap; // 0x68
	private Dictionary`2 m_homeBgDic; // 0x70
	private Dictionary`2 m_homeThemeDic; // 0x78
	private Dictionary`2 m_storyToVariantDict; // 0x80
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetHomeBgDataById; // 0x8
	private static DelegateBridge __Hotfix0_GetHomeThemeDataById; // 0x10
	private static DelegateBridge __Hotfix0_GetHomeBgDefaultMusicId; // 0x18
	private static DelegateBridge __Hotfix0_GetAvatarDataById; // 0x20
	private static DelegateBridge __Hotfix0_TryGetAvatarDataById; // 0x28
	private static DelegateBridge __Hotfix0_GetAvatarGroupDataByType; // 0x30
	private static DelegateBridge __Hotfix0_GetNameCardFixedModuleDataById; // 0x38
	private static DelegateBridge __Hotfix0_GetNameCardRemovableModuleDataById; // 0x40
	private static DelegateBridge __Hotfix0_GetNameCardSkinDataById; // 0x48
	private static DelegateBridge __Hotfix0__InitVariantDict; // 0x50
	private static DelegateBridge __Hotfix0_StoryVariantExist; // 0x58
	private static DelegateBridge __Hotfix0_GetStoryVariantId; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x31edf48 VA: 0x7595805f48
	protected override Void OnInit() { }
	// RVA: 0x31ee810 VA: 0x7595806810
	public HomeBackgroundSingleData GetHomeBgDataById(String id) { }
	// RVA: 0x31ee8d8 VA: 0x75958068d8
	public HomeThemeDisplayData GetHomeThemeDataById(String id) { }
	// RVA: 0x31ee9a0 VA: 0x75958069a0
	public String GetHomeBgDefaultMusicId() { }
	// RVA: 0x31eea34 VA: 0x7595806a34
	public PlayerAvatarPerData GetAvatarDataById(String id) { }
	// RVA: 0x31eeaf4 VA: 0x7595806af4
	public Boolean TryGetAvatarDataById(String id, out PlayerAvatarPerData data) { }
	// RVA: 0x31eebc8 VA: 0x7595806bc8
	public PlayerAvatarGroupData GetAvatarGroupDataByType(PlayerAvatarGroupType type) { }
	// RVA: 0x31eec7c VA: 0x7595806c7c
	public NameCardV2ModuleData GetNameCardFixedModuleDataById(String id) { }
	// RVA: 0x31eeda4 VA: 0x7595806da4
	public NameCardV2RemovableModuleData GetNameCardRemovableModuleDataById(String id) { }
	// RVA: 0x31eeecc VA: 0x7595806ecc
	public NameCardV2SkinData GetNameCardSkinDataById(String id) { }
	// RVA: 0x31ee458 VA: 0x7595806458
	private Void _InitVariantDict() { }
	// RVA: 0x31eeff4 VA: 0x7595806ff4
	public Boolean StoryVariantExist(String storyId, out List`1 variants) { }
	// RVA: 0x31ef0d4 VA: 0x75958070d4
	public String GetStoryVariantId(String storyId) { }
	// RVA: 0x31ef2c8 VA: 0x75958072c8
	public Void .ctor() { }
}
```