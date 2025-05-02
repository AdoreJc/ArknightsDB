# Act5D1RuneUtil

**Namespace:** `Torappu.Activity.Act5D1`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneUtil
{
	private const String RUNE_HUB_PATH; // 0x0
	private const String RUNE_BACK_HUB_PATH; // 0x0
	public const Int32 AVAILMASK; // 0x0
	public const Int32 UNLOCKMASK; // 0x0
	public static Int32 SELECT_PARAM; // 0x0
	public static Int32 NOT_SELECT_PARAM; // 0x4


	// RVA: 0x31c50e8 VA: 0x75957dd0e8
	public static PackedRuneData GetRuneData(String stageId, String runeId) { }
	// RVA: 0x31c5274 VA: 0x75957dd274
	public static RuneUnlockData GetRuneUnlockData(String stageId, String runeId) { }
	// RVA: 0x31c5398 VA: 0x75957dd398
	public static Boolean CheckRuneUnlocked(String stageId, String runeId) { }
	// RVA: 0x31c54b4 VA: 0x75957dd4b4
	public static RuneRecurrentStateData GetRecurrentData(String runeReCurrentId) { }
	// RVA: 0x31c55b8 VA: 0x75957dd5b8
	public static Boolean CheckRuneAvail(Int32 runeState) { }
	// RVA: 0x31c54ac VA: 0x75957dd4ac
	public static Boolean CheckRuneUnlocked(Int32 runeState) { }
	// RVA: 0x31c55c0 VA: 0x75957dd5c0
	public static String GetRunePath() { }
	// RVA: 0x31c5608 VA: 0x75957dd608
	public static String GetConstRunePathFromBattleFinish() { }
	// RVA: 0x31c5664 VA: 0x75957dd664
	public static String GetRuneBackPath() { }
	// RVA: 0x31c56ac VA: 0x75957dd6ac
	public static Boolean GetRuneSelectState(String key, Int32 defaultParam) { }
	// RVA: 0x31c579c VA: 0x75957dd79c
	public static Void SetRuneSelect(String stageId, String runeReId, String runeId, Boolean isSelect) { }
	// RVA: 0x31c5850 VA: 0x75957dd850
	public static Boolean GetRuneSelect(String stageId, String runeReId, String runeId) { }
	// RVA: 0x31c5938 VA: 0x75957dd938
	public static Sprite GetRuneSprite(String runeId, Boolean isFromBattleFinish) { }
	// RVA: 0x31c5ac4 VA: 0x75957ddac4
	public static Sprite GetRuneBackSprite(String bgPic) { }
	// RVA: 0x31c5bc4 VA: 0x75957ddbc4
	public Void .ctor() { }
	// RVA: 0x31c5bcc VA: 0x75957ddbcc
	private static Void .cctor() { }
}
```