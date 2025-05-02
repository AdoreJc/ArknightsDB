# VCharacterEmojiPanel

**Namespace:** `Torappu.Building.Vault.UI`


## Fields

- `RectTransform _prefabContainer`

- `VCharacter m_character`

- `Tween m_emojiTween`

- `VCharacterEmojiAnimItem m_curEmojiPrefab`


## Methods

- `Void BindVCharacter(VCharacter)`

- `Void UpdatePosition()`

- `Void Render(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault.UI
public class VCharacterEmojiPanel : MonoBehaviour, IHotfixable
{
	private RectTransform _prefabContainer; // 0x18
	private VCharacter m_character; // 0x20
	private Dictionary`2 m_emojiPrefabDict; // 0x28
	private Tween m_emojiTween; // 0x30
	private VCharacterEmojiAnimItem m_curEmojiPrefab; // 0x38
	private static DelegateBridge __Hotfix0_BindVCharacter; // 0x0
	private static DelegateBridge __Hotfix0_UpdatePosition; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d090d0 VA: 0x75963210d0
	public Void BindVCharacter(VCharacter character) { }
	// RVA: 0x3d0915c VA: 0x759632115c
	public Void UpdatePosition() { }
	// RVA: 0x3d095c8 VA: 0x75963215c8
	public Void Render(String emojiId) { }
	// RVA: 0x3d09840 VA: 0x7596321840
	public Void .ctor() { }
}
```