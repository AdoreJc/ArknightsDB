# HandBookV2OtherForceView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapAlphaDotView _dotView`

- `Image _backImg`

- `Text _forceName`

- `Text _forceName2`

- `GameObject _leftPart`

- `GameObject _rightPart`

- `HandBookV2GroupForceViewModel m_viewModel`

- `UIStringEvent onForceClick`


## Methods

- `Void OnClick()`

- `Void RenderView(HandBookV2GroupForceViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2OtherForceView : MonoBehaviour, IHotfixable
{
	private HandBookV2MapAlphaDotView _dotView; // 0x18
	private Image _backImg; // 0x20
	private Text _forceName; // 0x28
	private Text _forceName2; // 0x30
	private GameObject _leftPart; // 0x38
	private GameObject _rightPart; // 0x40
	private HandBookV2GroupForceViewModel m_viewModel; // 0x48
	public UIStringEvent onForceClick; // 0x50
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ed9b90 VA: 0x75954f1b90
	public Void OnClick() { }
	// RVA: 0x2ed5eec VA: 0x75954edeec
	public Void RenderView(HandBookV2GroupForceViewModel viewModel) { }
	// RVA: 0x2ed9c38 VA: 0x75954f1c38
	public Void .ctor() { }
}
```