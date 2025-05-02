# PlayerData

**Namespace:** `Torappu`


## Fields

- `String m_logToken`

- `String m_accessToken`

- `PlayerDataModel m_data`

- `JObject m_rawData`

- `ILuaPlayerData m_luaPlayerData`


## Properties

- `JsonSerializerSettings serializeSetting`

- `String logToken`

- `String accessToken`

- `String chatMask`

- `PlayerDataModel data`


## Methods

- `JsonSerializerSettings get_serializeSetting()`

- `String get_logToken()`

- `String get_accessToken()`

- `String get_chatMask()`

- `Void Init(PlayerDataModel, JObject)`

- `Void NotifyDataChanged(PlayerDataModel, PlayerDataDelta)`

- `Void _SyncDataToLua()`

- `PlayerDataModel get_data()`

- `JObject NetworkerOnlyRawData()`

- `Boolean CheckIfActivityExists(String)`

- `Boolean CheckIfSandboxExists(String)`

- `PlayerCharacter GetCharInstById(String)`

- `Void _OnDataChangeOnly_UpdateCharInstMap()`

- `Void _OnDataChangeOnly_UpdateExistActMap()`

- `Void _OnDataChangeOnly_UpdateExistSandboxPermSet()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerData : Singleton`1
{
	private const Int32 FAKE_CHAR_INST_ID_ROOT; // 0x0
	private const Int32 FAKE_CHAR_INST_ID_OFFSET; // 0x0
	private String m_logToken; // 0x10
	private String m_accessToken; // 0x18
	private PlayerDataModel m_data; // 0x20
	private JObject m_rawData; // 0x28
	private Dictionary`2 m_charIdInstMap; // 0x30
	private HashSet`1 m_existActSet; // 0x38
	private HashSet`1 m_existSandboxPermSet; // 0x40
	private ILuaPlayerData m_luaPlayerData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serializeSetting; // 0x8
	private static DelegateBridge __Hotfix0_get_logToken; // 0x10
	private static DelegateBridge __Hotfix0_get_accessToken; // 0x18
	private static DelegateBridge __Hotfix0_get_chatMask; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_NotifyDataChanged; // 0x30
	private static DelegateBridge __Hotfix0_LuaOnlyBindListener; // 0x38
	private static DelegateBridge __Hotfix0__SyncDataToLua; // 0x40
	private static DelegateBridge __Hotfix0_get_data; // 0x48
	private static DelegateBridge __Hotfix0_NetworkerOnlyRawData; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfActivityExists; // 0x58
	private static DelegateBridge __Hotfix0_CheckIfSandboxExists; // 0x60
	private static DelegateBridge __Hotfix0_GetCharInstById; // 0x68
	private static DelegateBridge __Hotfix0_GenerateFakeValidCharInstId; // 0x70
	private static DelegateBridge __Hotfix0_IsValidPlayerChar; // 0x78
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x80
	private static DelegateBridge __Hotfix0__OnDataChangeOnly_UpdateCharInstMap; // 0x88
	private static DelegateBridge __Hotfix0__OnDataChangeOnly_UpdateExistActMap; // 0x90
	private static DelegateBridge __Hotfix0__OnDataChangeOnly_UpdateExistSandboxPermSet; // 0x98

	public JsonSerializerSettings serializeSetting { get; }
	public String logToken { get; }
	public String accessToken { get; }
	public String chatMask { get; }
	public PlayerDataModel data { get; }

	// RVA: 0x33b0c48 VA: 0x75959c8c48
	private Void .ctor() { }
	// RVA: 0x33afbe8 VA: 0x75959c7be8
	public JsonSerializerSettings get_serializeSetting() { }
	// RVA: 0x33b0da4 VA: 0x75959c8da4
	public String get_logToken() { }
	// RVA: 0x33b0e0c VA: 0x75959c8e0c
	public String get_accessToken() { }
	// RVA: 0x33b0e74 VA: 0x75959c8e74
	public String get_chatMask() { }
	// RVA: 0x33b0ef0 VA: 0x75959c8ef0
	public Void Init(PlayerDataModel playerModel, JObject rawData) { }
	// RVA: 0x33b12b8 VA: 0x75959c92b8
	public Void NotifyDataChanged(PlayerDataModel newDataModel, PlayerDataDelta delta) { }
	// RVA: 0x33b1380 VA: 0x75959c9380
	public static Void LuaOnlyBindListener(ILuaPlayerData luaPlayerData) { }
	// RVA: 0x33b0fb8 VA: 0x75959c8fb8
	private Void _SyncDataToLua() { }
	// RVA: 0x33b1410 VA: 0x75959c9410
	public PlayerDataModel get_data() { }
	// RVA: 0x33b14bc VA: 0x75959c94bc
	public JObject NetworkerOnlyRawData() { }
	// RVA: 0x33b1524 VA: 0x75959c9524
	public Boolean CheckIfActivityExists(String actId) { }
	// RVA: 0x33b15e8 VA: 0x75959c95e8
	public Boolean CheckIfSandboxExists(String topicId) { }
	// RVA: 0x33b16ac VA: 0x75959c96ac
	public PlayerCharacter GetCharInstById(String charId) { }
	// RVA: 0x33b1768 VA: 0x75959c9768
	public static Int32 GenerateFakeValidCharInstId(Int32 bias, FakeInstType instType) { }
	// RVA: 0x33b17f0 VA: 0x75959c97f0
	public static Boolean IsValidPlayerChar(Int32 charInstId) { }
	// RVA: 0x33b185c VA: 0x75959c985c
	protected virtual Void OnPlayerDataChanged(PlayerDataModel prevData, PlayerDataDelta delta) { }
	// RVA: 0x33b19cc VA: 0x75959c99cc
	private Void _OnDataChangeOnly_UpdateCharInstMap() { }
	// RVA: 0x33b1b20 VA: 0x75959c9b20
	private Void _OnDataChangeOnly_UpdateExistActMap() { }
	// RVA: 0x33b1e6c VA: 0x75959c9e6c
	private Void _OnDataChangeOnly_UpdateExistSandboxPermSet() { }
}
```