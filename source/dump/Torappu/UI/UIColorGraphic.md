# UIColorGraphic

**Namespace:** `Torappu.UI`


## Fields

- `Color _color`

- `Boolean m_isOperating`


## Methods

- `Void AttachGraphic(Graphic, Boolean)`

- `Void AttachGraphicsWithGroup(List`1, String)`

- `Void _ApplyOptToGraphics(GraphicOpt, CommonParams)`

- `Color <>xLuaBaseProxy_get_color()`

- `Void <>xLuaBaseProxy_set_color(Color)`

- `Void <>xLuaBaseProxy_CrossFadeAlpha(Single, Single, Boolean)`

- `Void <>xLuaBaseProxy_CrossFadeColor(Color, Single, Boolean, Boolean, Boolean)`

- `Void <>xLuaBaseProxy_CrossFadeColor(Color, Single, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIColorGraphic : NonDrawingGraphic, IHotfixable
{
	private Graphic[] _colorElements; // 0xb0
	private Color _color; // 0xb8
	private Boolean m_isOperating; // 0xc8
	private List`1 m_dynList; // 0xd0
	private static DelegateBridge __Hotfix0_get_color; // 0x0
	private static DelegateBridge __Hotfix0_set_color; // 0x8
	private static DelegateBridge __Hotfix0_AttachGraphic; // 0x10
	private static DelegateBridge __Hotfix0_AttachGraphicsWithGroup; // 0x18
	private static DelegateBridge __Hotfix0_CrossFadeAlpha; // 0x20
	private static DelegateBridge __Hotfix0_CrossFadeColor; // 0x28
	private static DelegateBridge __Hotfix1_CrossFadeColor; // 0x30
	private static DelegateBridge __Hotfix0__ApplyOptToGraphics; // 0x38
	private static DelegateBridge __Hotfix0__CrossFadeAlpha; // 0x40
	private static DelegateBridge __Hotfix0__CrossFadeColorRGB; // 0x48
	private static DelegateBridge __Hotfix0__CrossFadeColorAlpha; // 0x50
	private static DelegateBridge __Hotfix0__SetColor; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override Color color { get; set; }

	// RVA: 0x21d18d4 VA: 0x75947e98d4
	public override Color get_color() { }
	// RVA: 0x21d193c VA: 0x75947e993c
	public override Void set_color(Color value) { }
	// RVA: 0x21d1d58 VA: 0x75947e9d58
	public Void AttachGraphic(Graphic graphic, Boolean useStaticColor) { }
	// RVA: 0x21d2068 VA: 0x75947ea068
	public Void AttachGraphicsWithGroup(List`1 graphic, String groupId) { }
	// RVA: 0x21d243c VA: 0x75947ea43c
	public override Void CrossFadeAlpha(Single alpha, Single duration, Boolean ignoreTimeScale) { }
	// RVA: 0x21d2574 VA: 0x75947ea574
	public override Void CrossFadeColor(Color targetColor, Single duration, Boolean ignoreTimeScale, Boolean useAlpha, Boolean useRGB) { }
	// RVA: 0x21d26ec VA: 0x75947ea6ec
	public override Void CrossFadeColor(Color targetColor, Single duration, Boolean ignoreTimeScale, Boolean useAlpha) { }
	// RVA: 0x21d1a60 VA: 0x75947e9a60
	private Void _ApplyOptToGraphics(GraphicOpt opt, CommonParams param) { }
	// RVA: 0x21d2868 VA: 0x75947ea868
	private static Void _CrossFadeAlpha(Graphic graphic, CommonParams param) { }
	// RVA: 0x21d2984 VA: 0x75947ea984
	private static Void _CrossFadeColorRGB(Graphic graphic, CommonParams param) { }
	// RVA: 0x21d2ab8 VA: 0x75947eaab8
	private static Void _CrossFadeColorAlpha(Graphic graphic, CommonParams param) { }
	// RVA: 0x21d2be4 VA: 0x75947eabe4
	private static Void _SetColor(Graphic graphic, CommonParams param) { }
	// RVA: 0x21d2cfc VA: 0x75947eacfc
	public Void .ctor() { }
	// RVA: 0x21d2d74 VA: 0x75947ead74
	private Color <>xLuaBaseProxy_get_color() { }
	// RVA: 0x21d2d80 VA: 0x75947ead80
	private Void <>xLuaBaseProxy_set_color(Color P0) { }
	// RVA: 0x21d2d88 VA: 0x75947ead88
	private Void <>xLuaBaseProxy_CrossFadeAlpha(Single P0, Single P1, Boolean P2) { }
	// RVA: 0x21d2d94 VA: 0x75947ead94
	private Void <>xLuaBaseProxy_CrossFadeColor(Color P0, Single P1, Boolean P2, Boolean P3, Boolean P4) { }
	// RVA: 0x21d2da8 VA: 0x75947eada8
	private Void <>xLuaBaseProxy_CrossFadeColor(Color P0, Single P1, Boolean P2, Boolean P3) { }
}
```