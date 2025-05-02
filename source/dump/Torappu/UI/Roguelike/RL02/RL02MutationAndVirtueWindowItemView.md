# RL02MutationAndVirtueWindowItemView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `GameObject _panelContent`

- `Image _imageIcon`

- `Text _textName`

- `Text _textEffect`

- `Text _textDesc`

- `UIAtlasImage _imageBkg`

- `UIAtlasObject _imageBkgAtlas`

- `String _imageBkgMutationName`

- `String _imageBkgVirtueName`

- `String m_cachedIconId`


## Methods

- `String _BuildMutationString(RoguelikeCharBuffModel, List`1)`

- `Void Render(String, RoguelikeCharBuffModel, List`1)`

- `Void Render(String, RoguelikeSquadBuffModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02MutationAndVirtueWindowItemView : MonoBehaviour, IHotfixable
{
	private const String MUTATION_DESC_COLOR; // 0x0
	private GameObject _panelContent; // 0x18
	private Image _imageIcon; // 0x20
	private Text _textName; // 0x28
	private Text _textEffect; // 0x30
	private Text _textDesc; // 0x38
	private UIAtlasImage _imageBkg; // 0x40
	private UIAtlasObject _imageBkgAtlas; // 0x48
	private String _imageBkgMutationName; // 0x50
	private String _imageBkgVirtueName; // 0x58
	private String m_cachedIconId; // 0x60
	private static DelegateBridge __Hotfix0__BuildMutationString; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix1_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b7012c VA: 0x759518812c
	private String _BuildMutationString(RoguelikeCharBuffModel mutation, List`1 mutationCharList) { }
	// RVA: 0x2b6faa4 VA: 0x7595187aa4
	public Void Render(String topicId, RoguelikeCharBuffModel mutation, List`1 mutationCharList) { }
	// RVA: 0x2b6ff5c VA: 0x7595187f5c
	public Void Render(String topicId, RoguelikeSquadBuffModel virtue) { }
	// RVA: 0x2b703b4 VA: 0x75951883b4
	public Void .ctor() { }
}
```