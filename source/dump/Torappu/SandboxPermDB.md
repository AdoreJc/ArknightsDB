# SandboxPermDB

**Namespace:** `Torappu`


## Methods

- `SandboxV2WeatherData GetSandboxV2WeatherDataByTypeAndLevel(String, SandboxV2WeatherType, Int32)`

- `Int32 GetSandboxV2NodeUpgradeRarityRequirement(String, SandboxV2ItemTrapTag)`

- `Boolean GetSandboxPermItemData(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxPermDB : ConstTable`2
{
	private Dictionary`2 m_sandboxV2WeatherDataDict; // 0x60
	private Dictionary`2 m_sandboxV2NodeUpgradeRarityRequirementDict; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetSandboxV2WeatherDataByTypeAndLevel; // 0x8
	private static DelegateBridge __Hotfix0_GetSandboxV2NodeUpgradeRarityRequirement; // 0x10
	private static DelegateBridge __Hotfix0_GetSandboxPermItemData; // 0x18
	private static DelegateBridge __Hotfix0_GetSandboxV2PrevNearestShopRefreshTime; // 0x20
	private static DelegateBridge __Hotfix0_GetSandboxV2PrevMonthRefreshTime; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31f65b4 VA: 0x759580e5b4
	protected override Void OnInit() { }
	// RVA: 0x31f6cd4 VA: 0x759580ecd4
	public SandboxV2WeatherData GetSandboxV2WeatherDataByTypeAndLevel(String topicId, SandboxV2WeatherType type, Int32 level) { }
	// RVA: 0x31f6e14 VA: 0x759580ee14
	public Int32 GetSandboxV2NodeUpgradeRarityRequirement(String topicId, SandboxV2ItemTrapTag itemTag) { }
	// RVA: 0x31f6f00 VA: 0x759580ef00
	public Boolean GetSandboxPermItemData(String itemId, out SandboxPermItemData itemData) { }
	// RVA: 0x31f6fcc VA: 0x759580efcc
	public static Int64 GetSandboxV2PrevNearestShopRefreshTime(String topicId, Int64 timestamp) { }
	// RVA: 0x31f71dc VA: 0x759580f1dc
	public static Int64 GetSandboxV2PrevMonthRefreshTime(String topicId, Int64 currTs) { }
	// RVA: 0x31f7410 VA: 0x759580f410
	public Void .ctor() { }
}
```