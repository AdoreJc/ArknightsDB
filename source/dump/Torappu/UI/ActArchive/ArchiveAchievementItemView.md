# ArchiveAchievementItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `TwoStateToggle _toggleIfCompleted`

- `UIAtlasImage _imgBkg`

- `UIAtlasObject _atlas`

- `Image _progress`

- `Text _textNameCompleted`

- `Text _textDescCompleted`

- `Text _textNameUncompleted`

- `Text _textDescUncompleted`


## Methods

- `Void Render(AchievementItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAchievementItemView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _toggleIfCompleted; // 0x18
	private UIAtlasImage _imgBkg; // 0x20
	private UIAtlasObject _atlas; // 0x28
	private Image _progress; // 0x30
	private Text _textNameCompleted; // 0x38
	private Text _textDescCompleted; // 0x40
	private Text _textNameUncompleted; // 0x48
	private Text _textDescUncompleted; // 0x50
	private const String BKG_NAME_FORMAT_WITH_DIFFERENT_RARITY; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30157ac VA: 0x759562d7ac
	public Void Render(AchievementItemModel itemModel) { }
	// RVA: 0x3015c9c VA: 0x759562dc9c
	public Void .ctor() { }
}
```