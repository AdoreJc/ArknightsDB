# FriendAliasView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `InputField _alias`

- `FriendListState _state`

- `UIRenderTextureImage _blurBack`

- `Shader _blurShader`

- `String m_uid`


## Methods

- `Void InitAlias(String, String)`

- `Void OnClick()`

- `Void OnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAliasView : MonoBehaviour
{
	private InputField _alias; // 0x18
	private FriendListState _state; // 0x20
	private UIRenderTextureImage _blurBack; // 0x28
	private Shader _blurShader; // 0x30
	private String m_uid; // 0x38


	// RVA: 0x28c7e14 VA: 0x7594edfe14
	public Void InitAlias(String alias, String uid) { }
	// RVA: 0x28c7e78 VA: 0x7594edfe78
	public Void OnClick() { }
	// RVA: 0x28c7f3c VA: 0x7594edff3c
	public Void OnCancel() { }
	// RVA: 0x28c7f8c VA: 0x7594edff8c
	public Void .ctor() { }
}
```