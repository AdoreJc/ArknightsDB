# ActivityCommonCheckinDotView

**Namespace:** `Torappu.Activity`


## Fields

- `Transform _container`

- `ActivityCommonCheckinDotObj _dotObj`

- `Int32 m_splitPos`

- `Single m_width`

- `GameObject m_whiteLine`

- `GameObject m_grayLine`


## Methods

- `Void RenderView(DotViewConfigGroup, List`1, Dictionary`2)`

- `Void _RenderLines(DotViewConfigGroup, Int32, Int32)`

- `Void _RenderDots(DotViewConfigGroup, List`1, Dictionary`2)`

- `Void _InstLine(DotViewConfigGroup, Int32, Int32)`

- `Void _UpdateWhiteLineTransform(GameObject, Int32, Int32)`

- `Void _UpdateGrayLineTransform(GameObject, Int32, Int32)`

- `Void _UpdateImagePos(ActivityCommonCheckinDotObj, Int32, Int32)`

- `Void _OnDotClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonCheckinDotView : MonoBehaviour, IHotfixable
{
	private const String LINE_NAME; // 0x0
	private const String DOT_NAME; // 0x0
	private const Int32 LINE_HEIGHT; // 0x0
	private Transform _container; // 0x18
	private ActivityCommonCheckinDotObj _dotObj; // 0x20
	private Int32 m_splitPos; // 0x28
	private Single m_width; // 0x2c
	private List`1 m_dotList; // 0x30
	private GameObject m_whiteLine; // 0x38
	private GameObject m_grayLine; // 0x40
	private Action`2 m_onDotClick; // 0x48
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0__RenderLines; // 0x8
	private static DelegateBridge __Hotfix0__RenderDots; // 0x10
	private static DelegateBridge __Hotfix0__InstLine; // 0x18
	private static DelegateBridge __Hotfix0__UpdateWhiteLineTransform; // 0x20
	private static DelegateBridge __Hotfix0__UpdateGrayLineTransform; // 0x28
	private static DelegateBridge __Hotfix0__UpdateImagePos; // 0x30
	private static DelegateBridge __Hotfix0__OnDotClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x30cd28c VA: 0x75956e528c
	public Void RenderView(DotViewConfigGroup configGroup, List`1 playerHistorys, Dictionary`2 checkInList) { }
	// RVA: 0x30cd414 VA: 0x75956e5414
	private Void _RenderLines(DotViewConfigGroup configGroup, Int32 splitPos, Int32 totalCount) { }
	// RVA: 0x30cd57c VA: 0x75956e557c
	private Void _RenderDots(DotViewConfigGroup configGroup, List`1 playerHistorys, Dictionary`2 checkInList) { }
	// RVA: 0x30cda64 VA: 0x75956e5a64
	private Void _InstLine(DotViewConfigGroup configGroup, Int32 cutPos, Int32 totalCount) { }
	// RVA: 0x30cdcb0 VA: 0x75956e5cb0
	private Void _UpdateWhiteLineTransform(GameObject lineObject, Int32 cutPos, Int32 totalCount) { }
	// RVA: 0x30cdddc VA: 0x75956e5ddc
	private Void _UpdateGrayLineTransform(GameObject lineObject, Int32 cutPos, Int32 totalCount) { }
	// RVA: 0x30cdf18 VA: 0x75956e5f18
	private Void _UpdateImagePos(ActivityCommonCheckinDotObj image, Int32 pos, Int32 totalCount) { }
	// RVA: 0x30ce018 VA: 0x75956e6018
	private Void _OnDotClick(Int32 index) { }
	// RVA: 0x30ce0e0 VA: 0x75956e60e0
	public Void .ctor() { }
}
```