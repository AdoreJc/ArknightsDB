# AIRLBattleLoader

**Namespace:** `Torappu.AIRL`


## Fields

- `ResourceCollector _collector`

- `Single m_startLoadingTime`


## Methods

- `IEnumerator Start()`

- `IEnumerator _DoLoad()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AIRL
public class AIRLBattleLoader : AbstractBattleLoader
{
	private ResourceCollector _collector; // 0x18
	private Single m_startLoadingTime; // 0x20
	private List`1 m_configs; // 0x28
	private HashSet`1 m_resourceSet; // 0x30
	private List`1 m_packedStages; // 0x38
	private static IConverter m_plainTextConverter; // 0x0
	private static DelegateBridge __Hotfix0_get_plainTextConverter; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0__DoLoad; // 0x18
	private static DelegateBridge __Hotfix0_get_BATTLE_SCENE; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private static IConverter plainTextConverter { get; }
	private static String BATTLE_SCENE { get; }

	// RVA: 0x3eedaa4 VA: 0x7596505aa4
	private static IConverter get_plainTextConverter() { }
	// RVA: 0x3eedb3c VA: 0x7596505b3c
	private IEnumerator Start() { }
	// RVA: 0x3eedc10 VA: 0x7596505c10
	private IEnumerator _DoLoad() { }
	// RVA: 0x3eedce4 VA: 0x7596505ce4
	private static String get_BATTLE_SCENE() { }
	// RVA: 0x3eedd58 VA: 0x7596505d58
	public Void .ctor() { }
}
```