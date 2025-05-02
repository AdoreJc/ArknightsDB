# CharacterLvlupExpCircleView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _imgBkg`

- `Image _imgCurrentProgress`

- `Image _imgAdditionProgress`

- `Color _colorNormalBkg`

- `Color _colorScrollingBkg`

- `Tween m_tween`

- `Int32 m_cachedLevel`

- `Single m_cachedAddProgress`


## Methods

- `Void Render(CharacterLvlupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupExpCircleView : MonoBehaviour, IHotfixable
{
	private const Single DURATION_SHOW; // 0x0
	private Image _imgBkg; // 0x18
	private Image _imgCurrentProgress; // 0x20
	private Image _imgAdditionProgress; // 0x28
	private Color _colorNormalBkg; // 0x30
	private Color _colorScrollingBkg; // 0x40
	private Tween m_tween; // 0x50
	private Int32 m_cachedLevel; // 0x58
	private Single m_cachedAddProgress; // 0x5c
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d74c14 VA: 0x759538cc14
	public Void Render(CharacterLvlupViewModel viewModel) { }
	// RVA: 0x2d74e64 VA: 0x759538ce64
	public Void .ctor() { }
}
```