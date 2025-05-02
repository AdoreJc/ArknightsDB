# BossRushSquadHomePluginView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `Image _imgRelicIcon`

- `GameObject _objRelicEmpty`

- `GameObject _objRelicHas`

- `GameObject _objTeamBuff`

- `Image _imgTeamBuffIcon`

- `UIFadeFloatPanel _fadeTeamBuffDetailTipsPanel`

- `Text _txtTeamBuffName`

- `Text _txtTeamBuffDec`

- `RectTransform _transTeamBuffDetailBlock`

- `GameObject _objTeamBuffBan`

- `Boolean m_hasInited`

- `Boolean m_isTipsBlockShowing`

- `String m_groupId`

- `String m_stageId`

- `BossRushStageType m_stageType`

- `Boolean m_curSquadHasTeamBuff`

- `String m_teamId`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateTeamBuffPart()`

- `Void _TryCloseTeamBuffDes()`

- `Void _ShowTeamBuffDetailTips(Boolean)`

- `Void _SetTeamBuffTipsVisible(Boolean)`

- `Void _TryTriggerAVG()`

- `Void EventOnRelicBtnClick()`

- `Void EventOnTeamBuffBtnClick()`

- `Void EventOnTeamBuffDetailBlockClick()`

- `Boolean <>xLuaBaseProxy_ShowSquadLeftArrow()`

- `Void <>xLuaBaseProxy_OnSquadGroupChanged(SquadGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushSquadHomePluginView : SquadHomePluginView
{
	private Image _imgRelicIcon; // 0x30
	private GameObject _objRelicEmpty; // 0x38
	private GameObject _objRelicHas; // 0x40
	private GameObject _objTeamBuff; // 0x48
	private Image _imgTeamBuffIcon; // 0x50
	private UIFadeFloatPanel _fadeTeamBuffDetailTipsPanel; // 0x58
	private Text _txtTeamBuffName; // 0x60
	private Text _txtTeamBuffDec; // 0x68
	private RectTransform _transTeamBuffDetailBlock; // 0x70
	private GameObject _objTeamBuffBan; // 0x78
	private Boolean m_hasInited; // 0x80
	private Boolean m_isTipsBlockShowing; // 0x81
	private String m_groupId; // 0x88
	private String m_stageId; // 0x90
	private BossRushStageType m_stageType; // 0x98
	private Boolean m_curSquadHasTeamBuff; // 0x9c
	private String m_teamId; // 0xa0
	private Dictionary`2 m_cachedTeamDataMap; // 0xa8
	private static DelegateBridge __Hotfix0_ShowSquadLeftArrow; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__UpdateTeamBuffPart; // 0x18
	private static DelegateBridge __Hotfix0__TryCloseTeamBuffDes; // 0x20
	private static DelegateBridge __Hotfix0__ShowTeamBuffDetailTips; // 0x28
	private static DelegateBridge __Hotfix0__SetTeamBuffTipsVisible; // 0x30
	private static DelegateBridge __Hotfix0__TryTriggerAVG; // 0x38
	private static DelegateBridge __Hotfix0_EventOnRelicBtnClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnTeamBuffBtnClick; // 0x48
	private static DelegateBridge __Hotfix0_EventOnTeamBuffDetailBlockClick; // 0x50
	private static DelegateBridge __Hotfix0_OnSquadGroupChanged; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2e64fdc VA: 0x759547cfdc
	public override Boolean ShowSquadLeftArrow() { }
	// RVA: 0x2e65040 VA: 0x759547d040
	public override Void Show(PluginInputParams param) { }
	// RVA: 0x2e652c8 VA: 0x759547d2c8
	private Void _InitIfNot() { }
	// RVA: 0x2e65488 VA: 0x759547d488
	private Void _UpdateTeamBuffPart() { }
	// RVA: 0x2e656d8 VA: 0x759547d6d8
	private Void _TryCloseTeamBuffDes() { }
	// RVA: 0x2e65628 VA: 0x759547d628
	private Void _ShowTeamBuffDetailTips(Boolean show) { }
	// RVA: 0x2e65758 VA: 0x759547d758
	private Void _SetTeamBuffTipsVisible(Boolean visible) { }
	// RVA: 0x2e653cc VA: 0x759547d3cc
	private Void _TryTriggerAVG() { }
	// RVA: 0x2e6581c VA: 0x759547d81c
	public Void EventOnRelicBtnClick() { }
	// RVA: 0x2e65910 VA: 0x759547d910
	public Void EventOnTeamBuffBtnClick() { }
	// RVA: 0x2e6597c VA: 0x759547d97c
	public Void EventOnTeamBuffDetailBlockClick() { }
	// RVA: 0x2e659e8 VA: 0x759547d9e8
	protected override Void OnSquadGroupChanged(SquadGroupViewModel groupModel) { }
	// RVA: 0x2e65af8 VA: 0x759547daf8
	public Void .ctor() { }
	// RVA: 0x2e65b68 VA: 0x759547db68
	private Boolean <>xLuaBaseProxy_ShowSquadLeftArrow() { }
	// RVA: 0x2e65b70 VA: 0x759547db70
	private Void <>xLuaBaseProxy_OnSquadGroupChanged(SquadGroupViewModel P0) { }
}
```