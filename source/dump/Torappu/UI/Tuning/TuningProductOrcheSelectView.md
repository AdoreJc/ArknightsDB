# TuningProductOrcheSelectView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductPagerView _pagerView`

- `Int32 m_cachedEnterSequenceNum`

- `Boolean m_isInited`


## Methods

- `Void Render(TuningProductViewModel)`

- `Void SetFormEffectHide()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductOrcheSelectView : MonoBehaviour, IHotfixable
{
	private TuningProductPagerView _pagerView; // 0x18
	private List`1 _orcheTypeToFormEffectViewList; // 0x20
	public Action`1 onSelectOrche; // 0x28
	private Int32 m_cachedEnterSequenceNum; // 0x30
	private Boolean m_isInited; // 0x34
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_SetFormEffectHide; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x233637c VA: 0x759494e37c
	public Void Render(TuningProductViewModel model) { }
	// RVA: 0x23366c8 VA: 0x759494e6c8
	public Void SetFormEffectHide() { }
	// RVA: 0x23364fc VA: 0x759494e4fc
	private Void _InitIfNot() { }
	// RVA: 0x23367b0 VA: 0x759494e7b0
	public Void .ctor() { }
}
```