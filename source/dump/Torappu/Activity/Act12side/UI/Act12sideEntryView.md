# Act12sideEntryView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Act12sideCoinView _coinView`

- `Text _textStageTimeCaption`

- `Text _textRewardTimeCaption`

- `Text _textEndTime`

- `Text _textRemainTime`

- `GameObject _btnCharmNormalGo`

- `GameObject _btnCharmLockGo`

- `Text _textCharmLockHint`

- `Button _btnCharm`

- `Boolean m_hasInited`

- `String m_actId`

- `AudioClickPlayer m_btnCharmAudio`


## Methods

- `Void Render(String)`

- `Void _InitIfNot()`

- `Void _RefreshTimePanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideEntryView : MonoBehaviour, IHotfixable
{
	private Act12sideCoinView _coinView; // 0x18
	private Text _textStageTimeCaption; // 0x20
	private Text _textRewardTimeCaption; // 0x28
	private Text _textEndTime; // 0x30
	private Text _textRemainTime; // 0x38
	private GameObject _btnCharmNormalGo; // 0x40
	private GameObject _btnCharmLockGo; // 0x48
	private Text _textCharmLockHint; // 0x50
	private Button _btnCharm; // 0x58
	private Boolean m_hasInited; // 0x60
	private String m_actId; // 0x68
	private AudioClickPlayer m_btnCharmAudio; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RefreshTimePanel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x34621b0 VA: 0x7595a7a1b0
	public Void Render(String activityId) { }
	// RVA: 0x3462324 VA: 0x7595a7a324
	private Void _InitIfNot() { }
	// RVA: 0x34623d8 VA: 0x7595a7a3d8
	private Void _RefreshTimePanel() { }
	// RVA: 0x34628b4 VA: 0x7595a7a8b4
	public Void .ctor() { }
}
```