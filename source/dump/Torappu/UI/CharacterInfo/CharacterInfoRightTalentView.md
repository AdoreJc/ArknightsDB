# CharacterInfoRightTalentView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _talentName`

- `Text _textContent`

- `CharacterInfoTalentUnlockView _unlockView`

- `Single _initHeight`

- `CharacterTalentViewModel m_viewModel`

- `TextGenerator m_textGenerate`


## Methods

- `Single CalcHeight()`

- `Void Render(CharacterTalentViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightTalentView : MonoBehaviour
{
	private Text _talentName; // 0x18
	private Text _textContent; // 0x20
	private CharacterInfoTalentUnlockView _unlockView; // 0x28
	private Single _initHeight; // 0x30
	private CharacterTalentViewModel m_viewModel; // 0x38
	private TextGenerator m_textGenerate; // 0x68


	// RVA: 0x2d850ec VA: 0x759539d0ec
	public Single CalcHeight() { }
	// RVA: 0x2d85104 VA: 0x759539d104
	public Void Render(CharacterTalentViewModel viewModel) { }
	// RVA: 0x2d854b8 VA: 0x759539d4b8
	public Void .ctor() { }
}
```