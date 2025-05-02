# MultilineBestFit

**Namespace:** `Torappu.UI`


## Fields

- `Text m_text`

- `Int32 m_defaultSize`

- `String m_processedContent`

- `Font m_processedFont`

- `String m_textForFit`

- `HorizontalWrapMode m_preHorzMode`

- `VerticalWrapMode m_preVertMode`

- `TextAnchor m_cacheTextAnchor`

- `Boolean _binary`

- `Boolean _ignoreBlankEnd`

- `Int32 _minSize`

- `Boolean _autoAlignmentWhenOnlyOneLine`

- `TextAnchor _textAnchorWhenOnlyOneLine`


## Methods

- `Boolean _GetAutoAlignmentWhenOnlyOneLine()`

- `Void LateUpdate()`

- `Void TryFit()`

- `Int32 _BinaryFind()`

- `Int32 _DecreaseFind()`

- `Boolean _CheckSuitable(Int32, Vector2)`

- `Void <>xLuaBaseProxy_Awake()`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class MultilineBestFit : UIBehaviour, IHotfixable
{
	private Text m_text; // 0x18
	private Int32 m_defaultSize; // 0x20
	private String m_processedContent; // 0x28
	private Font m_processedFont; // 0x30
	private String m_textForFit; // 0x38
	private HorizontalWrapMode m_preHorzMode; // 0x40
	private VerticalWrapMode m_preVertMode; // 0x44
	private TextAnchor m_cacheTextAnchor; // 0x48
	private Boolean _binary; // 0x4c
	private Boolean _ignoreBlankEnd; // 0x4d
	private Int32 _minSize; // 0x50
	private Boolean _autoAlignmentWhenOnlyOneLine; // 0x54
	private TextAnchor _textAnchorWhenOnlyOneLine; // 0x58
	private static DelegateBridge __Hotfix0__GetAutoAlignmentWhenOnlyOneLine; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x20
	private static DelegateBridge __Hotfix0_TryFit; // 0x28
	private static DelegateBridge __Hotfix0__BinaryFind; // 0x30
	private static DelegateBridge __Hotfix0__DecreaseFind; // 0x38
	private static DelegateBridge __Hotfix0__CheckSuitable; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2195c9c VA: 0x75947adc9c
	private Boolean _GetAutoAlignmentWhenOnlyOneLine() { }
	// RVA: 0x2195d04 VA: 0x75947add04
	protected override Void Awake() { }
	// RVA: 0x2195dd4 VA: 0x75947addd4
	protected override Void OnEnable() { }
	// RVA: 0x2195e50 VA: 0x75947ade50
	protected override Void OnDisable() { }
	// RVA: 0x2195ed8 VA: 0x75947aded8
	private Void LateUpdate() { }
	// RVA: 0x2195f40 VA: 0x75947adf40
	private Void TryFit() { }
	// RVA: 0x2196364 VA: 0x75947ae364
	private Int32 _BinaryFind() { }
	// RVA: 0x2196290 VA: 0x75947ae290
	private Int32 _DecreaseFind() { }
	// RVA: 0x219647c VA: 0x75947ae47c
	private Boolean _CheckSuitable(Int32 fontSize, Vector2 extents) { }
	// RVA: 0x21967a0 VA: 0x75947ae7a0
	public Void .ctor() { }
	// RVA: 0x2196810 VA: 0x75947ae810
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x2196818 VA: 0x75947ae818
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x2196820 VA: 0x75947ae820
	private Void <>xLuaBaseProxy_OnDisable() { }
}
```