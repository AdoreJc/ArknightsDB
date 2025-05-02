# BattleInfoCache

**Namespace:** `Torappu.UI`


## Fields

- `Data m_data`

- `ContinuousData m_continuousData`

- `Boolean m_isRestartGame`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class BattleInfoCache : Singleton`1
{
	private Data m_data; // 0x10
	private ContinuousData m_continuousData; // 0x40
	private Boolean m_isRestartGame; // 0x50
	private List`1 m_restartCompleteTimes; // 0x58
	public static UInt32 cacheStartUniqueId; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_get_data; // 0x10
	private static DelegateBridge __Hotfix0_CacheData; // 0x18
	private static DelegateBridge __Hotfix0_get_continuousData; // 0x20
	private static DelegateBridge __Hotfix0_get_isRestartGame; // 0x28
	private static DelegateBridge __Hotfix0_get_restartCompleteTimes; // 0x30
	private static DelegateBridge __Hotfix0_CacheContinuousData; // 0x38
	private static DelegateBridge __Hotfix0_get_hasContinuousData; // 0x40
	private static DelegateBridge __Hotfix0_ClearContinuousData; // 0x48
	private static DelegateBridge __Hotfix0_SetIsRestartGame; // 0x50
	private static DelegateBridge __Hotfix0_CacheCompleteTimeBeforeRestart; // 0x58
	private static DelegateBridge __Hotfix0_ClearRestartData; // 0x60

	public static Data data { get; }
	public static ContinuousData continuousData { get; }
	public static Boolean isRestartGame { get; }
	public static List`1 restartCompleteTimes { get; }
	public static Boolean hasContinuousData { get; }

	// RVA: 0x210f7d8 VA: 0x75947277d8
	private Void .ctor() { }
	// RVA: 0x210f8bc VA: 0x75947278bc
	public static Data get_data() { }
	// RVA: 0x210f960 VA: 0x7594727960
	public static Void CacheData(Data paramData) { }
	// RVA: 0x210fa28 VA: 0x7594727a28
	public static ContinuousData get_continuousData() { }
	// RVA: 0x210fab0 VA: 0x7594727ab0
	public static Boolean get_isRestartGame() { }
	// RVA: 0x210fb34 VA: 0x7594727b34
	public static List`1 get_restartCompleteTimes() { }
	// RVA: 0x210fbb8 VA: 0x7594727bb8
	public static Void CacheContinuousData(ContinuousData contData) { }
	// RVA: 0x210fc60 VA: 0x7594727c60
	public static Boolean get_hasContinuousData() { }
	// RVA: 0x210fcf4 VA: 0x7594727cf4
	public static Void ClearContinuousData() { }
	// RVA: 0x210fd78 VA: 0x7594727d78
	public static Void SetIsRestartGame(Boolean isRestartGame) { }
	// RVA: 0x210fe08 VA: 0x7594727e08
	public static Void CacheCompleteTimeBeforeRestart(Int32 completeTime) { }
	// RVA: 0x210ff04 VA: 0x7594727f04
	public static Void ClearRestartData() { }
}
```