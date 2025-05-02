# CharmListAdapter

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `CharmCard _charmCardPrefab`

- `CharmCardMode _mode`

- `Action onFirstCharmRegistered`

- `Boolean m_avgTraceRegistered`


## Methods

- `Void _TraceAVG(Int32, CharmCardHolder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmListAdapter : RecycleLoopScrollAdapter`2
{
	private CharmCard _charmCardPrefab; // 0x68
	private CharmCardMode _mode; // 0x70
	public Action`1 onSelectChanged; // 0x78
	public Action onFirstCharmRegistered; // 0x80
	private Boolean m_avgTraceRegistered; // 0x88
	private static DelegateBridge __Hotfix0_UpdateView; // 0x0
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x8
	private static DelegateBridge __Hotfix0__TraceAVG; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x34525a0 VA: 0x7595a6a5a0
	public override Void UpdateView(Int32 position, GameObject view, CharmCardHolder holder, CharmModel data) { }
	// RVA: 0x3452854 VA: 0x7595a6a854
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x34526ec VA: 0x7595a6a6ec
	private Void _TraceAVG(Int32 position, CharmCardHolder holder) { }
	// RVA: 0x3452920 VA: 0x7595a6a920
	public Void .ctor() { }
}
```