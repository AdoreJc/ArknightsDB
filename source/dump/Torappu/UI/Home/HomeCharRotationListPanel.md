# HomeCharRotationListPanel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _chosenSkinCount`

- `Text _skinMaxCount`

- `TwoStateToggle _setAssistToggle`

- `SimpleLayoutContent _content`

- `String m_secretarySkinId`

- `String m_selectedSkinId`

- `Adapter m_adapter`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(HomeCharRotationViewModel, Int32)`

- `Void OnSetSecretary()`

- `Void OpenChangeSecretarySkinState()`

- `Void _OnClicked(String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationListPanel : MonoBehaviour, IHotfixable
{
	private Text _chosenSkinCount; // 0x18
	private Text _skinMaxCount; // 0x20
	private TwoStateToggle _setAssistToggle; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private String m_secretarySkinId; // 0x38
	private String m_selectedSkinId; // 0x40
	private ListDict`2 m_cachedSkinItems; // 0x48
	private Adapter m_adapter; // 0x50
	private Boolean m_hasInited; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnSetSecretary; // 0x8
	private static DelegateBridge __Hotfix0_OpenChangeSecretarySkinState; // 0x10
	private static DelegateBridge __Hotfix0__OnClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x282c774 VA: 0x7594e44774
	public Void Render(HomeCharRotationViewModel model, Int32 skinMaxCnt) { }
	// RVA: 0x282c9dc VA: 0x7594e449dc
	public Void OnSetSecretary() { }
	// RVA: 0x282cacc VA: 0x7594e44acc
	public Void OpenChangeSecretarySkinState() { }
	// RVA: 0x282cb70 VA: 0x7594e44b70
	private Void _OnClicked(String skinId) { }
	// RVA: 0x282c90c VA: 0x7594e4490c
	private Void _InitIfNot() { }
	// RVA: 0x282cd00 VA: 0x7594e44d00
	public Void .ctor() { }
}
```