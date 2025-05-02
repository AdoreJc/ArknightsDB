# CharacterEvolveTextContainer

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _textObj`


## Methods

- `Void Render(CharacterInfoEvolveInfoViewModel)`

- `Void _InstAndRetext(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterEvolveTextContainer : MonoBehaviour, IHotfixable
{
	private Text _textObj; // 0x18
	private List`1 m_textList; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InstAndRetext; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d70198 VA: 0x7595388198
	public Void Render(CharacterInfoEvolveInfoViewModel viewModel) { }
	// RVA: 0x2d70938 VA: 0x7595388938
	private Void _InstAndRetext(String template, String value) { }
	// RVA: 0x2d70bf0 VA: 0x7595388bf0
	public Void .ctor() { }
}
```