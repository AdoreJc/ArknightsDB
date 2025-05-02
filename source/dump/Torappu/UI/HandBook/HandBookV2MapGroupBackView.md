# HandBookV2MapGroupBackView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapDotView _dotView`

- `HandBookV2GroupCharViewModel m_viewModel`

- `HandBookV2GroupColorBlockViewModel m_colorViewModel`


## Methods

- `Void RenderView(HandBookV2GroupCharViewModel, String)`

- `Void RenderView(HandBookV2GroupColorBlockViewModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapGroupBackView : MonoBehaviour, IHotfixable
{
	private HandBookV2MapDotView _dotView; // 0x18
	private HandBookV2GroupCharViewModel m_viewModel; // 0x20
	private HandBookV2GroupColorBlockViewModel m_colorViewModel; // 0x28
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix1_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ed2c10 VA: 0x75954eac10
	public Void RenderView(HandBookV2GroupCharViewModel viewModel, String mainGroup) { }
	// RVA: 0x2ed2cec VA: 0x75954eacec
	public Void RenderView(HandBookV2GroupColorBlockViewModel viewModel, String mainGroup) { }
	// RVA: 0x2ed2dc8 VA: 0x75954eadc8
	public Void .ctor() { }
}
```