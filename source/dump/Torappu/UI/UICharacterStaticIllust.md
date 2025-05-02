# UICharacterStaticIllust

**Namespace:** `Torappu.UI`


## Fields

- `IllustHandler m_handler`

- `Tween m_fadeTweener`

- `Image m_image`

- `EventTrigger m_onClickTrigger`

- `ClickOption m_onClickOption`

- `UICharIllustPluginGraphics m_pluginGraphics`

- `String <illustId>k__BackingField`


## Methods

- `Void Init(IllustHandler, String, Image)`

- `Void _EventOnClickEvent()`

- `Void <RegisterClick>b__42_0(BaseEventData)`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy_RegisterClick(ClickOption)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterStaticIllust : UICharacterIllust
{
	private const Single CHAR_INFO_SPREAD_PANEL_ZOOM_MAX; // 0x0
	private const Single CHAR_INFO_SPREAD_MAX_ZOOM_WITH_PLUGIN; // 0x0
	private IllustHandler m_handler; // 0x18
	private Tween m_fadeTweener; // 0x20
	private Image m_image; // 0x28
	private EventTrigger m_onClickTrigger; // 0x30
	private ClickOption m_onClickOption; // 0x38
	private List`1 m_graphicList; // 0x48
	private UICharIllustPluginGraphics m_pluginGraphics; // 0x50
	private String <illustId>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_illustId; // 0x0
	private static DelegateBridge __Hotfix0_set_illustId; // 0x8
	private static DelegateBridge __Hotfix0_get_isDynamic; // 0x10
	private static DelegateBridge __Hotfix0_get_isActiveIllust; // 0x18
	private static DelegateBridge __Hotfix0_get_rectTransform; // 0x20
	private static DelegateBridge __Hotfix0_get_mainGraphic; // 0x28
	private static DelegateBridge __Hotfix0_get_raycastTarget; // 0x30
	private static DelegateBridge __Hotfix0_set_raycastTarget; // 0x38
	private static DelegateBridge __Hotfix0_get_color; // 0x40
	private static DelegateBridge __Hotfix0_set_color; // 0x48
	private static DelegateBridge __Hotfix0_get_alpha; // 0x50
	private static DelegateBridge __Hotfix0_get_mainTexture; // 0x58
	private static DelegateBridge __Hotfix0_get_rawSize; // 0x60
	private static DelegateBridge __Hotfix0_get_graphics; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x78
	private static DelegateBridge __Hotfix0_Activate; // 0x80
	private static DelegateBridge __Hotfix0_SetAlpha; // 0x88
	private static DelegateBridge __Hotfix0_DOFade; // 0x90
	private static DelegateBridge __Hotfix0_ApplySkinOffset; // 0x98
	private static DelegateBridge __Hotfix0_GetCharInfoSpreadPanelZoomMax; // 0xa0
	private static DelegateBridge __Hotfix0_RegisterClick; // 0xa8
	private static DelegateBridge __Hotfix0_GetMainMaterial; // 0xb0
	private static DelegateBridge __Hotfix0_SetMainMaterial; // 0xb8
	private static DelegateBridge __Hotfix0__EventOnClickEvent; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public override String illustId { get; set; }
	public override Boolean isDynamic { get; }
	public override Boolean isActiveIllust { get; }
	public override RectTransform rectTransform { get; }
	protected override Graphic mainGraphic { get; }
	public override Boolean raycastTarget { get; set; }
	public override Color color { get; set; }
	public override Single alpha { get; }
	public override Texture mainTexture { get; }
	public override Vector2 rawSize { get; }
	public override IList`1 graphics { get; }

	// RVA: 0x2137294 VA: 0x759474f294
	public override String get_illustId() { }
	// RVA: 0x21372fc VA: 0x759474f2fc
	protected override Void set_illustId(String value) { }
	// RVA: 0x2137380 VA: 0x759474f380
	public override Boolean get_isDynamic() { }
	// RVA: 0x21373e4 VA: 0x759474f3e4
	public override Boolean get_isActiveIllust() { }
	// RVA: 0x213745c VA: 0x759474f45c
	public override RectTransform get_rectTransform() { }
	// RVA: 0x21374d0 VA: 0x759474f4d0
	protected override Graphic get_mainGraphic() { }
	// RVA: 0x2137538 VA: 0x759474f538
	public override Boolean get_raycastTarget() { }
	// RVA: 0x21375c4 VA: 0x759474f5c4
	public override Void set_raycastTarget(Boolean value) { }
	// RVA: 0x2137668 VA: 0x759474f668
	public override Color get_color() { }
	// RVA: 0x21376e4 VA: 0x759474f6e4
	public override Void set_color(Color value) { }
	// RVA: 0x213797c VA: 0x759474f97c
	public override Single get_alpha() { }
	// RVA: 0x21379f4 VA: 0x759474f9f4
	public override Texture get_mainTexture() { }
	// RVA: 0x2137a70 VA: 0x759474fa70
	public override Vector2 get_rawSize() { }
	// RVA: 0x2137b88 VA: 0x759474fb88
	public override IList`1 get_graphics() { }
	// RVA: 0x2137ddc VA: 0x759474fddc
	protected override Void OnDestroy() { }
	// RVA: 0x2137e64 VA: 0x759474fe64
	public Void Init(IllustHandler handler, String illustId, Image staticIllust) { }
	// RVA: 0x2137f60 VA: 0x759474ff60
	public override Void Activate(Boolean fastMode) { }
	// RVA: 0x2138010 VA: 0x7594750010
	public override Void SetAlpha(Single alpha) { }
	// RVA: 0x2138180 VA: 0x7594750180
	public override Tween DOFade(Single endValue, Single duration) { }
	// RVA: 0x21383bc VA: 0x75947503bc
	public override Void ApplySkinOffset() { }
	// RVA: 0x2138500 VA: 0x7594750500
	public override Single GetCharInfoSpreadPanelZoomMax() { }
	// RVA: 0x21385b0 VA: 0x75947505b0
	public override Void RegisterClick(ClickOption clickOption) { }
	// RVA: 0x2138810 VA: 0x7594750810
	public override Material GetMainMaterial() { }
	// RVA: 0x213888c VA: 0x759475088c
	public override Void SetMainMaterial(Material mat) { }
	// RVA: 0x21389f8 VA: 0x75947509f8
	private Void _EventOnClickEvent() { }
	// RVA: 0x2138a7c VA: 0x7594750a7c
	public Void .ctor() { }
	// RVA: 0x2138ae8 VA: 0x7594750ae8
	private Void <RegisterClick>b__42_0(BaseEventData data) { }
	// RVA: 0x2138aec VA: 0x7594750aec
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x2138af0 VA: 0x7594750af0
	private Void <>xLuaBaseProxy_RegisterClick(ClickOption P0) { }
}
```