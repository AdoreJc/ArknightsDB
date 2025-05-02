# UICommonPageEffectHolder

**Namespace:** `Torappu.UI`


## Fields

- `ScreenEffectHolder _effectHolder`

- `Boolean m_isInited`

- `UIRendererSortingInfoStorage m_sortingInfo`

- `UIPage m_registeredPage`


## Methods

- `Void Bind(UIPage)`

- `Void Unbind()`

- `Void SetEffectEnable(Boolean)`

- `Void InitSortingInfo(SortingInfo)`

- `Void AdjustToTargetLayer(SortingInfo)`

- `Void RestoreLayers()`

- `Void _BindToPage()`

- `Void _UnbindFromPage()`

- `Void _InitCacheIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommonPageEffectHolder : MonoBehaviour, IPageUIRenderer, IHotfixable
{
	private ScreenEffectHolder _effectHolder; // 0x18
	private Boolean m_isInited; // 0x20
	private UIRendererSortingInfoStorage m_sortingInfo; // 0x28
	private UIPage m_registeredPage; // 0x30
	private static DelegateBridge __Hotfix0_Bind; // 0x0
	private static DelegateBridge __Hotfix0_Unbind; // 0x8
	private static DelegateBridge __Hotfix0_SetEffectEnable; // 0x10
	private static DelegateBridge __Hotfix0_InitSortingInfo; // 0x18
	private static DelegateBridge __Hotfix0_AdjustToTargetLayer; // 0x20
	private static DelegateBridge __Hotfix0_RestoreLayers; // 0x28
	private static DelegateBridge __Hotfix0__BindToPage; // 0x30
	private static DelegateBridge __Hotfix0__UnbindFromPage; // 0x38
	private static DelegateBridge __Hotfix0__InitCacheIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x21d3564 VA: 0x75947eb564
	public Void Bind(UIPage pageToBind) { }
	// RVA: 0x21d3700 VA: 0x75947eb700
	public Void Unbind() { }
	// RVA: 0x21d3860 VA: 0x75947eb860
	public Void SetEffectEnable(Boolean enable) { }
	// RVA: 0x21d38ec VA: 0x75947eb8ec
	public Void InitSortingInfo(SortingInfo sortingInfo) { }
	// RVA: 0x21d3b0c VA: 0x75947ebb0c
	public Void AdjustToTargetLayer(SortingInfo sortingInfo) { }
	// RVA: 0x21d3bc0 VA: 0x75947ebbc0
	public Void RestoreLayers() { }
	// RVA: 0x21d3640 VA: 0x75947eb640
	private Void _BindToPage() { }
	// RVA: 0x21d37a0 VA: 0x75947eb7a0
	private Void _UnbindFromPage() { }
	// RVA: 0x21d39a0 VA: 0x75947eb9a0
	private Void _InitCacheIfNot() { }
	// RVA: 0x21d3c48 VA: 0x75947ebc48
	public Void .ctor() { }
}
```