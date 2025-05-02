# Act4D0StoryView

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `ScrollRect _rect`

- `String m_activityId`


## Methods

- `Void RenderInfo(List`1, Action`1, Boolean)`

- `IEnumerator _RefreshTargetState(Single)`

- `Void _OnItemClickCallBack(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0StoryView : MonoBehaviour, IHotfixable
{
	private List`1 _itemList; // 0x18
	private ScrollRect _rect; // 0x20
	private Action`1 m_callback; // 0x28
	private String m_activityId; // 0x30
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x0
	private static DelegateBridge __Hotfix0__RefreshTargetState; // 0x8
	private static DelegateBridge __Hotfix0__OnItemClickCallBack; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31df68c VA: 0x75957f768c
	public Void RenderInfo(List`1 viewModel, Action`1 callback, Boolean needScroll) { }
	// RVA: 0x31e0054 VA: 0x75957f8054
	private IEnumerator _RefreshTargetState(Single index) { }
	// RVA: 0x31e0140 VA: 0x75957f8140
	private Void _OnItemClickCallBack(Int32 index) { }
	// RVA: 0x31e01e0 VA: 0x75957f81e0
	public Void .ctor() { }
}
```