# Act3D0MileStoneHolder

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Text _title`

- `LoopVerticalScrollRect _content`

- `Act3D0MileStoneGridAdapter _adapter`

- `Image _backImage`

- `UIStringEvent _clickEvent`


## Methods

- `Void RefreshInfo(List`1, Int32)`

- `Void RenderInfo(List`1, Int32)`

- `IEnumerator _RefreshTargetState(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0MileStoneHolder : MonoBehaviour, IHotfixable
{
	private Text _title; // 0x18
	private LoopVerticalScrollRect _content; // 0x20
	private Act3D0MileStoneGridAdapter _adapter; // 0x28
	private Image _backImage; // 0x30
	private UIStringEvent _clickEvent; // 0x38
	private static DelegateBridge __Hotfix0_RefreshInfo; // 0x0
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x8
	private static DelegateBridge __Hotfix0__RefreshTargetState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32310f8 VA: 0x75958490f8
	public Void RefreshInfo(List`1 viewModelList, Int32 count) { }
	// RVA: 0x323086c VA: 0x759584886c
	public Void RenderInfo(List`1 viewModelList, Int32 count) { }
	// RVA: 0x3235cd4 VA: 0x759584dcd4
	private IEnumerator _RefreshTargetState(Single index) { }
	// RVA: 0x3235dc0 VA: 0x759584ddc0
	public Void .ctor() { }
}
```