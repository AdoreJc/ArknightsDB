# BossRushBattleFinishRewardItemView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `Image _imgItem`

- `Text _textName`

- `Text _textItemCount`

- `Text _textMax`

- `GameObject _firstPassTagGo`

- `Text _textFirstPassCount`

- `LayoutElement _layoutElement`

- `Single _normalWidth`

- `Single _firstPassWidth`


## Methods

- `Void Render(String, Boolean, Int32, Int32, Boolean)`

- `String _GetFormatCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushBattleFinishRewardItemView : MonoBehaviour, IHotfixable
{
	private Image _imgItem; // 0x18
	private Text _textName; // 0x20
	private Text _textItemCount; // 0x28
	private Text _textMax; // 0x30
	private GameObject _firstPassTagGo; // 0x38
	private Text _textFirstPassCount; // 0x40
	private LayoutElement _layoutElement; // 0x48
	private Single _normalWidth; // 0x50
	private Single _firstPassWidth; // 0x54
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetFormatCount; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2e5467c VA: 0x759546c67c
	public Void Render(String itemId, Boolean isMax, Int32 itemCount, Int32 firstPassCount, Boolean forcedShowNormal) { }
	// RVA: 0x2e549e8 VA: 0x759546c9e8
	private String _GetFormatCount(Int32 rewardCount) { }
	// RVA: 0x2e54aac VA: 0x759546caac
	public Void .ctor() { }
}
```