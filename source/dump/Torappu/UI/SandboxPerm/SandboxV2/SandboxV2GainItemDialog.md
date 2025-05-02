# SandboxV2GainItemDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _viewContainer`

- `RectTransform _bactRt`

- `UIRenderTextureImage _blurFloat`

- `SandboxV2GainItemView m_gainItemView`

- `Boolean m_showItemDetail`

- `Action m_cachedCallback`

- `Boolean m_hasInited`


## Methods

- `Void OnClick()`

- `Void _InitIfNot()`

- `Void _OnItemCardClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2GainItemDialog : UICustomDialog`1, IHotfixable
{
	private RectTransform _viewContainer; // 0x50
	private RectTransform _bactRt; // 0x58
	private UIRenderTextureImage _blurFloat; // 0x60
	private SandboxV2GainItemView m_gainItemView; // 0x68
	private IList`1 m_cachedItemModels; // 0x70
	private Boolean m_showItemDetail; // 0x78
	private Action m_cachedCallback; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnItemCardClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x25c848c VA: 0x7594be048c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x25c84f4 VA: 0x7594be04f4
	protected override Void OnRender(Options options) { }
	// RVA: 0x25c8a0c VA: 0x7594be0a0c
	protected override UISwitchTween GenerateShowTween() { }
	// RVA: 0x25c8ad4 VA: 0x7594be0ad4
	public Void OnClick() { }
	// RVA: 0x25c871c VA: 0x7594be071c
	private Void _InitIfNot() { }
	// RVA: 0x25c8c30 VA: 0x7594be0c30
	private Void _OnItemCardClick(Int32 index) { }
	// RVA: 0x25c8e14 VA: 0x7594be0e14
	public Void .ctor() { }
}
```