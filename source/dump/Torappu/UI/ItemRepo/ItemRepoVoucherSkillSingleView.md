# ItemRepoVoucherSkillSingleView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Image _specialIcon`

- `GameObject _training`

- `GameObject _btnSelect`

- `CharacterInfoSkillView _skillView`


## Methods

- `Void Render(SkillItemViewModel, ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherSkillSingleView : MonoBehaviour, IHotfixable
{
	private Image _specialIcon; // 0x18
	private GameObject[] _specLevel; // 0x20
	private GameObject _training; // 0x28
	private GameObject _btnSelect; // 0x30
	protected CharacterInfoSkillView _skillView; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d3bef0 VA: 0x7595353ef0
	public Void Render(SkillItemViewModel viewModel, ILoadAsset assetLoader) { }
	// RVA: 0x2d3c084 VA: 0x7595354084
	public Void .ctor() { }
}
```