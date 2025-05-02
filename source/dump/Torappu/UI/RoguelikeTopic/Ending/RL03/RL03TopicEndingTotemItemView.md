# RL03TopicEndingTotemItemView

**Namespace:** `Torappu.UI.RoguelikeTopic.Ending.RL03`


## Fields

- `RL03TotemItemView _totemPrefab`

- `Transform _totemContainer`

- `Text _name`

- `Text _desc`

- `Single _totemScale`

- `Boolean m_isInited`

- `RL03TotemItemView m_view`


## Methods

- `Void Render(RL03TotemViewModel, ILoadAsset)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Ending.RL03
public class RL03TopicEndingTotemItemView : MonoBehaviour, IHotfixable
{
	private RL03TotemItemView _totemPrefab; // 0x18
	private Transform _totemContainer; // 0x20
	private Text _name; // 0x28
	private Text _desc; // 0x30
	private Single _totemScale; // 0x38
	private Boolean m_isInited; // 0x3c
	private RL03TotemItemView m_view; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26db490 VA: 0x7594cf3490
	public Void Render(RL03TotemViewModel viewModel, ILoadAsset assetLoader) { }
	// RVA: 0x26db5dc VA: 0x7594cf35dc
	private Void _InitIfNot() { }
	// RVA: 0x26db6f0 VA: 0x7594cf36f0
	public Void .ctor() { }
}
```