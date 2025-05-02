# Act1VAutoChessEntryModeChoiceSubBackView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessEntryModeChoiceBackEnterExitAnim _enterExitAnim`

- `Boolean m_isInited`

- `Int32 m_cachedEnterSeqNum`

- `String m_cachedFocusingMode`

- `Tween m_focusAnimTween`


## Methods

- `Void _InitIfNot()`

- `Void _PlayModeFocusAnim(String)`

- `Void _UpdateEnterExitAnim()`

- `Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryModeChoiceSubBackView : Act1VAutoChessBaseSubView
{
	private List`1 _animConfigs; // 0x18
	private Act1VAutoChessEntryModeChoiceBackEnterExitAnim _enterExitAnim; // 0x20
	private Boolean m_isInited; // 0x28
	private Dictionary`2 m_animConfigMap; // 0x30
	private Int32 m_cachedEnterSeqNum; // 0x38
	private String m_cachedFocusingMode; // 0x40
	private Tween m_focusAnimTween; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__PlayModeFocusAnim; // 0x10
	private static DelegateBridge __Hotfix0__UpdateEnterExitAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3344c70 VA: 0x759595cc70
	public override Void Render(Act1VAutoChessEntryBaseSubViewModel subViewModel) { }
	// RVA: 0x3344de4 VA: 0x759595cde4
	private Void _InitIfNot() { }
	// RVA: 0x3345014 VA: 0x759595d014
	private Void _PlayModeFocusAnim(String modeId) { }
	// RVA: 0x334521c VA: 0x759595d21c
	private Void _UpdateEnterExitAnim() { }
	// RVA: 0x33452fc VA: 0x759595d2fc
	public Void .ctor() { }
	// RVA: 0x3345368 VA: 0x759595d368
	private Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel P0) { }
}
```