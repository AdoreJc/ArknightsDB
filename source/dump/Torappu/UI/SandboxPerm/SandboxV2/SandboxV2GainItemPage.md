# SandboxV2GainItemPage

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _viewContainer`

- `RectTransform _backRt`

- `UIBlurFloatPanel _blurFloatPanel`

- `SandboxV2GainItemView m_gainItemView`

- `Boolean m_showItemDetail`

- `Action m_cachedCallback`

- `Boolean m_hasInited`


## Methods

- `Void OnClick()`

- `Void OnRender(Options)`

- `Void _InitIfNot()`

- `Void _OnItemCardClick(Int32)`

- `Void _TutorialOnly_TryRaiseAVGSignal()`

- `IEnumerator <>n__0(Boolean)`

- `IEnumerator <>n__1(Boolean)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2GainItemPage : UIPage, IPauseBattlePage
{
	private RectTransform _viewContainer; // 0xd0
	private RectTransform _backRt; // 0xd8
	private UIBlurFloatPanel _blurFloatPanel; // 0xe0
	private SandboxV2GainItemView m_gainItemView; // 0xe8
	private IList`1 m_cachedItemModels; // 0xf0
	private Boolean m_showItemDetail; // 0xf8
	private Action m_cachedCallback; // 0x100
	private Boolean m_hasInited; // 0x108
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_OnRender; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnItemCardClick; // 0x28
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseAVGSignal; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x25c9324 VA: 0x7594be1324
	public override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x25c9414 VA: 0x7594be1414
	protected override IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x25c9504 VA: 0x7594be1504
	public Void OnClick() { }
	// RVA: 0x25c95cc VA: 0x7594be15cc
	private Void OnRender(Options options) { }
	// RVA: 0x25c97f4 VA: 0x7594be17f4
	private Void _InitIfNot() { }
	// RVA: 0x25c98fc VA: 0x7594be18fc
	private Void _OnItemCardClick(Int32 index) { }
	// RVA: 0x25c9a48 VA: 0x7594be1a48
	private Void _TutorialOnly_TryRaiseAVGSignal() { }
	// RVA: 0x25c9aec VA: 0x7594be1aec
	public Void .ctor() { }
	// RVA: 0x25c9b5c VA: 0x7594be1b5c
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x25c9b68 VA: 0x7594be1b68
	private IEnumerator <>n__1(Boolean isIntoStack) { }
	// RVA: 0x25c9b74 VA: 0x7594be1b74
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
	// RVA: 0x25c9b80 VA: 0x7594be1b80
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean P0) { }
}
```