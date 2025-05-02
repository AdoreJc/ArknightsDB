# Act1LockInterlockStageStatusView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `GameObject _notDefend`

- `GameObject _isDefended`


## Methods

- `Void RenderStatus(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockInterlockStageStatusView : MonoBehaviour, IHotfixable
{
	private GameObject _notDefend; // 0x18
	private GameObject _isDefended; // 0x20
	private static DelegateBridge __Hotfix0_RenderStatus; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x33cd924 VA: 0x75959e5924
	public Void RenderStatus(Boolean isInterlocked) { }
	// RVA: 0x33cd9bc VA: 0x75959e59bc
	public Void .ctor() { }
}
```