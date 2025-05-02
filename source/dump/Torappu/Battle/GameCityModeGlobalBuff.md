# GameCityModeGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `FP m_waveDuration`

- `FP m_restDuration`

- `String m_startTrapIds`

- `GameCityGameMode m_gameMode`


## Methods

- `Void _GetArcgachaDataFromBlackboard()`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GameCityModeGlobalBuff : GlobalBuff
{
	private const String ARCGACHA_OBJECT_PREFIX; // 0x0
	private const String ARCGACHA_OBJECT_COUNT_KEY; // 0x0
	private const String ARCGACHA_OBJECT_WEIGHT_KEY; // 0x0
	private FP m_waveDuration; // 0xe0
	private FP m_restDuration; // 0xe8
	private String m_startTrapIds; // 0xf0
	private GameCityGameMode m_gameMode; // 0xf8
	private Dictionary`2 m_tempData; // 0x100
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__GetArcgachaDataFromBlackboard; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x4018510 VA: 0x7596630510
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x4018804 VA: 0x7596630804
	private Void _GetArcgachaDataFromBlackboard() { }
	// RVA: 0x4018d94 VA: 0x7596630d94
	public Void .ctor() { }
	// RVA: 0x4018e98 VA: 0x7596630e98
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
}
```