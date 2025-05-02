# CharacterLvlupLevelAnchorView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _objTopAnchor`

- `Text _txtTopLevel`

- `GameObject _objNormalBottomAnchor`

- `Text _txtNormalBottomLevel`

- `GameObject _objScrollBottomAnchor`

- `Text _txtScrollBottomLevel`

- `Action onMoveToMaxValidLevel`


## Methods

- `Void Render(CharacterLvlupViewModel)`

- `Void EventOnAnchorClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupLevelAnchorView : MonoBehaviour, IHotfixable
{
	private GameObject _objTopAnchor; // 0x18
	private Text _txtTopLevel; // 0x20
	private GameObject _objNormalBottomAnchor; // 0x28
	private Text _txtNormalBottomLevel; // 0x30
	private GameObject _objScrollBottomAnchor; // 0x38
	private Text _txtScrollBottomLevel; // 0x40
	public Action onMoveToMaxValidLevel; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnAnchorClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d75e78 VA: 0x759538de78
	public Void Render(CharacterLvlupViewModel viewModel) { }
	// RVA: 0x2d78104 VA: 0x7595390104
	public Void EventOnAnchorClick() { }
	// RVA: 0x2d78188 VA: 0x7595390188
	public Void .ctor() { }
}
```