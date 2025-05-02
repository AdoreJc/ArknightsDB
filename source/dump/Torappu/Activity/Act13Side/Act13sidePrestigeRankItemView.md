# Act13sidePrestigeRankItemView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Image _imgGradientBg`

- `Image _imgOrg`

- `Image _imgEmoji`

- `Text _textPrestigeRank`

- `GameObject _docItemGo`

- `Text _textDocCount`

- `GameObject _newsItemGo`

- `Text _textNewsCount`

- `GameObject _avgItemGo`

- `Text _textAvgCount`

- `GameObject _keyItemGo`

- `Text _textKeyName`

- `GameObject _completedGo`

- `GameObject _incomeGo`

- `Text _textUnlockHint`

- `GameObject _currentRankSignGo`


## Methods

- `Void Render(Int32, String, OrgData, PrestigeData, PrestigeRank)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sidePrestigeRankItemView : MonoBehaviour, IHotfixable
{
	private Color[] _gradientColorList; // 0x18
	private Image _imgGradientBg; // 0x20
	private Image _imgOrg; // 0x28
	private Image _imgEmoji; // 0x30
	private Text _textPrestigeRank; // 0x38
	private GameObject _docItemGo; // 0x40
	private Text _textDocCount; // 0x48
	private GameObject _newsItemGo; // 0x50
	private Text _textNewsCount; // 0x58
	private GameObject _avgItemGo; // 0x60
	private Text _textAvgCount; // 0x68
	private GameObject _keyItemGo; // 0x70
	private Text _textKeyName; // 0x78
	private GameObject _completedGo; // 0x80
	private GameObject _incomeGo; // 0x88
	private Text _textUnlockHint; // 0x90
	private GameObject _currentRankSignGo; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3434df4 VA: 0x7595a4cdf4
	public Void Render(Int32 position, String actId, OrgData orgData, PrestigeData prestigeData, PrestigeRank currentRank) { }
	// RVA: 0x3444214 VA: 0x7595a5c214
	public Void .ctor() { }
}
```