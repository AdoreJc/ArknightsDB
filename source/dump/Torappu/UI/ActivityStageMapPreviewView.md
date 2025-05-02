# ActivityStageMapPreviewView

**Namespace:** `Torappu.UI`


## Fields

- `UIBlurFloatPanel _blurPanel`

- `UIDynImage _imgPreview`

- `RectTransform _backPressRect`

- `Action <onBtnCloseClicked>k__BackingField`

- `Boolean m_Inited`


## Properties

- `Action onBtnCloseClicked`


## Methods

- `Action get_onBtnCloseClicked()`

- `Void set_onBtnCloseClicked(Action)`

- `Void OnClickClose()`

- `Void Show(String, Boolean)`

- `Void InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ActivityStageMapPreviewView : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _blurPanel; // 0x18
	private UIDynImage _imgPreview; // 0x20
	private RectTransform _backPressRect; // 0x28
	private Action <onBtnCloseClicked>k__BackingField; // 0x30
	private Boolean m_Inited; // 0x38
	private static DelegateBridge __Hotfix0_get_onBtnCloseClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnCloseClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnClickClose; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Action onBtnCloseClicked { get; set; }

	// RVA: 0x20fd724 VA: 0x7594715724
	public Action get_onBtnCloseClicked() { }
	// RVA: 0x20fd78c VA: 0x759471578c
	public Void set_onBtnCloseClicked(Action value) { }
	// RVA: 0x20fd810 VA: 0x7594715810
	public Void OnClickClose() { }
	// RVA: 0x20fd8bc VA: 0x75947158bc
	public Void Show(String stageId, Boolean forceReload) { }
	// RVA: 0x20fd9a4 VA: 0x75947159a4
	private Void InitIfNot() { }
	// RVA: 0x20fdc0c VA: 0x7594715c0c
	public Void .ctor() { }
}
```