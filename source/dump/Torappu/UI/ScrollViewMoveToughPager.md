# ScrollViewMoveToughPager

**Namespace:** `Torappu.UI`


## Fields

- `DateTime m_time`

- `Single m_cache`


## Methods

- `Void <>xLuaBaseProxy__OnBeginDrag(PointerEventData)`

- `Void <>xLuaBaseProxy__OnEndDrag(PointerEventData)`

- `Single <>xLuaBaseProxy__ScrollValue2PageIndex(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ScrollViewMoveToughPager : ScrollViewPager
{
	private DateTime m_time; // 0x70
	private Single m_cache; // 0x78
	private const Single DELTATHEROTIME; // 0x0
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x0
	private static DelegateBridge __Hotfix0__OnEndDrag; // 0x8
	private static DelegateBridge __Hotfix0__ScrollValue2PageIndex; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x223a54c VA: 0x759485254c
	protected override Void _OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x223a68c VA: 0x759485268c
	protected override Void _OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x223aa78 VA: 0x7594852a78
	protected override Single _ScrollValue2PageIndex(Single value) { }
	// RVA: 0x223ab0c VA: 0x7594852b0c
	public Void .ctor() { }
	// RVA: 0x223abfc VA: 0x7594852bfc
	private Void <>xLuaBaseProxy__OnBeginDrag(PointerEventData P0) { }
	// RVA: 0x223aca0 VA: 0x7594852ca0
	private Void <>xLuaBaseProxy__OnEndDrag(PointerEventData P0) { }
	// RVA: 0x223ad50 VA: 0x7594852d50
	private Single <>xLuaBaseProxy__ScrollValue2PageIndex(Single P0) { }
}
```