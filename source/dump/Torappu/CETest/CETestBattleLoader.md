# CETestBattleLoader

**Namespace:** `Torappu.CETest`


## Fields

- `ResourceCollector _collector`

- `Single m_startLoadingTime`


## Methods

- `IEnumerator Start()`

- `IEnumerator _DoLoad()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.CETest
public class CETestBattleLoader : AbstractBattleLoader
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
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private static IConverter plainTextConverter { get; }

	// RVA: 0x376ca34 VA: 0x7595d84a34
	private static IConverter get_plainTextConverter() { }
	// RVA: 0x376cacc VA: 0x7595d84acc
	private IEnumerator Start() { }
	// RVA: 0x376cba0 VA: 0x7595d84ba0
	private IEnumerator _DoLoad() { }
	// RVA: 0x376cc74 VA: 0x7595d84c74
	public Void .ctor() { }
}
```