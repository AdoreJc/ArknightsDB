# UIMessageText

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Vector2 _floatOffset`

- `Color _color`

- `Text m_label`


## Methods

- `Void Init(String, Transform)`

- `Void Init(String, Transform, Color)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIMessageText : UIPopup
{
	private Vector2 _floatOffset; // 0x2c
	private Color _color; // 0x34
	private Text m_label; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix1_Init; // 0x8
	private static DelegateBridge __Hotfix0_SetTweens; // 0x10
	private static DelegateBridge __Hotfix0_Awake; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2081a14 VA: 0x7594699a14
	public Void Init(String message, Transform spawnPoint) { }
	// RVA: 0x2081c24 VA: 0x7594699c24
	public Void Init(String message, Transform spawnPoint, Color color) { }
	// RVA: 0x2081d54 VA: 0x7594699d54
	protected override Void SetTweens(Single duration) { }
	// RVA: 0x2081f0c VA: 0x7594699f0c
	private Void Awake() { }
	// RVA: 0x2081f9c VA: 0x7594699f9c
	public Void .ctor() { }
}
```