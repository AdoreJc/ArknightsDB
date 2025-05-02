# UIHintController

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Int32 m_currentBannerIndex`

- `Boolean _isDownward`

- `Single _scrollSpeed`

- `Single _gapHeight`

- `Single _midLine`

- `Single _fadeInDuration`

- `Single _fadeOutDuration`

- `ScrollController m_scrollController`


## Methods

- `Void Awake()`

- `Void Show(String, BannerStyle)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIHintController : MonoBehaviour
{
	private List`1 _banners; // 0x18
	private Int32 m_currentBannerIndex; // 0x20
	private Sprite[] _bannerBackgroundImage; // 0x28
	private Boolean _isDownward; // 0x30
	private Single _scrollSpeed; // 0x34
	private Single _gapHeight; // 0x38
	private Single _midLine; // 0x3c
	private Single _fadeInDuration; // 0x40
	private Single _fadeOutDuration; // 0x44
	private ScrollController m_scrollController; // 0x48


	// RVA: 0x2042184 VA: 0x759465a184
	private Void Awake() { }
	// RVA: 0x20424c4 VA: 0x759465a4c4
	public Void Show(String text, BannerStyle style) { }
	// RVA: 0x2042618 VA: 0x759465a618
	private Void Update() { }
	// RVA: 0x2042978 VA: 0x759465a978
	public Void .ctor() { }
}
```