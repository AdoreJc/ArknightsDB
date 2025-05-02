# ActivityStageDynEntry

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `ActivityStageSingleComponent _entry`


## Properties

- `ActivityStageSingleComponent entry`


## Methods

- `ActivityStageSingleComponent get_entry()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class ActivityStageDynEntry : MonoBehaviour, IHotfixable
{
	private List`1 _components; // 0x18
	private ActivityStageSingleComponent _entry; // 0x20
	private static DelegateBridge __Hotfix0_get_components; // 0x0
	private static DelegateBridge __Hotfix0_get_entry; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public List`1 components { get; }
	public ActivityStageSingleComponent entry { get; }

	// RVA: 0x30b475c VA: 0x75956cc75c
	public List`1 get_components() { }
	// RVA: 0x30b47c4 VA: 0x75956cc7c4
	public ActivityStageSingleComponent get_entry() { }
	// RVA: 0x30b5d38 VA: 0x75956cdd38
	public Void .ctor() { }
}
```