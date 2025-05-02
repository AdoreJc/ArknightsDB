# TuningProductPagerView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `ScrollViewPager _scrollViewPager`

- `Single _spaceStep`

- `GameObject _leftArrow`

- `GameObject _rightArrow`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `Int32 m_orcheIdViewPairCnt`


## Methods

- `Void Render(ListDict`2)`

- `Void ResetPagerPosToDefault()`

- `Void _InitIfNot()`

- `Void _SetArrowActive(Single)`

- `TuningProductOrcheItemView _GetItemView(Int32)`

- `Void _SampleMovingAnim(Single)`

- `String _GetSelectItemId(Int32)`

- `Void _OnInstPagerUpdating(Single)`

- `Void _OnInstPageChangeEnd(Int32)`

- `Void OnClickLeftArrow()`

- `Void OnClickRightArrow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductPagerView : MonoBehaviour, IHotfixable
{
	private ScrollViewPager _scrollViewPager; // 0x18
	private List`1 _orcheViewList; // 0x20
	private Single _spaceStep; // 0x28
	private GameObject _leftArrow; // 0x30
	private GameObject _rightArrow; // 0x38
	private Boolean m_hasInited; // 0x40
	private ListDict`2 m_cachedOrcheModelListDict; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private Int32 m_orcheIdViewPairCnt; // 0x60
	public Action`1 onSelectOrche; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetPagerPosToDefault; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SetArrowActive; // 0x18
	private static DelegateBridge __Hotfix0__GetItemView; // 0x20
	private static DelegateBridge __Hotfix0__SampleMovingAnim; // 0x28
	private static DelegateBridge __Hotfix0__GetSelectItemId; // 0x30
	private static DelegateBridge __Hotfix0__OnInstPagerUpdating; // 0x38
	private static DelegateBridge __Hotfix0__OnInstPageChangeEnd; // 0x40
	private static DelegateBridge __Hotfix0_OnClickLeftArrow; // 0x48
	private static DelegateBridge __Hotfix0_OnClickRightArrow; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2331968 VA: 0x7594949968
	public Void Render(ListDict`2 orcheModelListDict) { }
	// RVA: 0x233183c VA: 0x759494983c
	public Void ResetPagerPosToDefault() { }
	// RVA: 0x2336820 VA: 0x759494e820
	private Void _InitIfNot() { }
	// RVA: 0x2336b2c VA: 0x759494eb2c
	private Void _SetArrowActive(Single zoneIndex) { }
	// RVA: 0x2336be8 VA: 0x759494ebe8
	private TuningProductOrcheItemView _GetItemView(Int32 position) { }
	// RVA: 0x23369e8 VA: 0x759494e9e8
	private Void _SampleMovingAnim(Single pagerVal) { }
	// RVA: 0x2336c84 VA: 0x759494ec84
	private String _GetSelectItemId(Int32 index) { }
	// RVA: 0x2336d84 VA: 0x759494ed84
	private Void _OnInstPagerUpdating(Single pagerVal) { }
	// RVA: 0x2336e04 VA: 0x759494ee04
	private Void _OnInstPageChangeEnd(Int32 zoneIndex) { }
	// RVA: 0x2336ecc VA: 0x759494eecc
	public Void OnClickLeftArrow() { }
	// RVA: 0x2336f64 VA: 0x759494ef64
	public Void OnClickRightArrow() { }
	// RVA: 0x233701c VA: 0x759494f01c
	public Void .ctor() { }
}
```