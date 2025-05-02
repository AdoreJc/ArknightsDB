# NameCardV2CollectModuleModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `String nickName`

- `String nickNameId`

- `Boolean isSpTheme`

- `String themeName`

- `String themeEnName`

- `DateTime registerDate`

- `Int32 birthMonth`

- `Int32 birthDay`

- `Int32 charCount`

- `Int32 charCollectPercent`

- `OperatorProgressStyle operatorShowStyle`

- `Int32 skinCount`

- `CharacterData charData`

- `Boolean m_hasTeamIconInited`


## Methods

- `Void _InitTeamCountListIfNot()`

- `Void _CleanTeamCountList()`

- `Void _LoadSpThemeInfo()`

- `Void SwitchOperatorStyle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2CollectModuleModel : NameCardV2ModuleBaseModel
{
	public String nickName; // 0x38
	public String nickNameId; // 0x40
	public Boolean isSpTheme; // 0x48
	public String themeName; // 0x50
	public String themeEnName; // 0x58
	public DateTime registerDate; // 0x60
	public Int32 birthMonth; // 0x68
	public Int32 birthDay; // 0x6c
	public Int32 charCount; // 0x70
	public Int32 charCollectPercent; // 0x74
	public OperatorProgressStyle operatorShowStyle; // 0x78
	public Int32 skinCount; // 0x7c
	public CharacterData charData; // 0x80
	public List`1 teamCountList; // 0x88
	private Boolean m_hasTeamIconInited; // 0x90
	private static DelegateBridge __Hotfix0_OnLoadFriendData; // 0x0
	private static DelegateBridge __Hotfix0_OnLoadSelfData; // 0x8
	private static DelegateBridge __Hotfix0_OnRefreshSelfData; // 0x10
	private static DelegateBridge __Hotfix0__InitTeamCountListIfNot; // 0x18
	private static DelegateBridge __Hotfix0__CleanTeamCountList; // 0x20
	private static DelegateBridge __Hotfix0__LoadSpThemeInfo; // 0x28
	private static DelegateBridge __Hotfix0_SwitchOperatorStyle; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x28c1b78 VA: 0x7594ed9b78
	protected override Void OnLoadFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28c2a50 VA: 0x7594edaa50
	protected override Void OnLoadSelfData() { }
	// RVA: 0x28c30f8 VA: 0x7594edb0f8
	protected override Void OnRefreshSelfData() { }
	// RVA: 0x28c2354 VA: 0x7594eda354
	private Void _InitTeamCountListIfNot() { }
	// RVA: 0x28c280c VA: 0x7594eda80c
	private Void _CleanTeamCountList() { }
	// RVA: 0x28c2984 VA: 0x7594eda984
	private Void _LoadSpThemeInfo() { }
	// RVA: 0x28c0984 VA: 0x7594ed8984
	public Void SwitchOperatorStyle() { }
	// RVA: 0x28c1464 VA: 0x7594ed9464
	public Void .ctor() { }
}
```