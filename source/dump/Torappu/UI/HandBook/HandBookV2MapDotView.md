# HandBookV2MapDotView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2AlphaHexagonView _dotSprite`

- `Action <onDotClick>k__BackingField`


## Properties

- `Action onDotClick`


## Methods

- `Action get_onDotClick()`

- `Void set_onDotClick(Action)`

- `Void OnDotClick()`

- `Void RenderColor(String, Boolean)`

- `Void Render(HandBookV2PointData, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapDotView : MonoBehaviour, IHotfixable
{
	private HandBookV2AlphaHexagonView _dotSprite; // 0x18
	private Action <onDotClick>k__BackingField; // 0x20
	private const Single backAlpha; // 0x0
	private const Single dotAlpha; // 0x0
	private static DelegateBridge __Hotfix0_get_onDotClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onDotClick; // 0x8
	private static DelegateBridge __Hotfix0_OnDotClick; // 0x10
	private static DelegateBridge __Hotfix0_RenderColor; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action onDotClick { get; set; }

	// RVA: 0x2ed0f6c VA: 0x75954e8f6c
	private Action get_onDotClick() { }
	// RVA: 0x2ed0fd4 VA: 0x75954e8fd4
	public Void set_onDotClick(Action value) { }
	// RVA: 0x2ed1058 VA: 0x75954e9058
	public Void OnDotClick() { }
	// RVA: 0x2ed10f4 VA: 0x75954e90f4
	public Void RenderColor(String colorStr, Boolean isCharUnlock) { }
	// RVA: 0x2ed11f0 VA: 0x75954e91f0
	public Void Render(HandBookV2PointData pointData, String htmlColor, Boolean isForceUnlock) { }
	// RVA: 0x2ed1324 VA: 0x75954e9324
	public Void .ctor() { }
}
```