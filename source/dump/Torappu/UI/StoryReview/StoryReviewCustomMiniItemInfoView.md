# StoryReviewCustomMiniItemInfoView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `GameObject _readBg`

- `GameObject _unreadBg`

- `GameObject _newTag`

- `GameObject _readMask`

- `Image _charImg`


## Methods

- `Void Render(Sprite, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewCustomMiniItemInfoView : MonoBehaviour, IHotfixable
{
	private GameObject _readBg; // 0x18
	private GameObject _unreadBg; // 0x20
	private GameObject _newTag; // 0x28
	private GameObject _readMask; // 0x30
	private Image _charImg; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x275eb08 VA: 0x7594d76b08
	public Void Render(Sprite charSprite, Boolean locked, Boolean read) { }
	// RVA: 0x275ebfc VA: 0x7594d76bfc
	public Void .ctor() { }
}
```