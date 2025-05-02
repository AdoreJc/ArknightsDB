# UIFakeBlur

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIFullScreenImage _fakeBlurImage`

- `Shader _blurShader`

- `Single _fadeTime`

- `Tweener m_tweener`

- `Sprite m_fakeSprite`

- `Boolean m_isOn`

- `Coroutine m_coroutine`

- `Color m_fakeColor`


## Properties

- `Boolean isOn`


## Methods

- `Boolean get_isOn()`

- `Coroutine Enter(Action)`

- `Coroutine Leave()`

- `Sprite ShotBlurBackground()`

- `Void SetSpriteColor(Color)`

- `Void _ClearIfNot(Boolean)`

- `IEnumerator _DoEnter(Action)`

- `IEnumerator _DoLeave()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIFakeBlur : MonoBehaviour
{
	private UIFullScreenImage _fakeBlurImage; // 0x18
	private Shader _blurShader; // 0x20
	private Single _fadeTime; // 0x28
	private Tweener m_tweener; // 0x30
	private Sprite m_fakeSprite; // 0x38
	private Boolean m_isOn; // 0x40
	private Coroutine m_coroutine; // 0x48
	private Color m_fakeColor; // 0x50

	public Boolean isOn { get; }

	// RVA: 0x207d270 VA: 0x7594695270
	protected virtual List`1 GetBlurCameras() { }
	// RVA: 0x207d400 VA: 0x7594695400
	public Boolean get_isOn() { }
	// RVA: 0x207d408 VA: 0x7594695408
	public Coroutine Enter(Action finishCb) { }
	// RVA: 0x207d644 VA: 0x7594695644
	public Coroutine Leave() { }
	// RVA: 0x207d710 VA: 0x7594695710
	public Sprite ShotBlurBackground() { }
	// RVA: 0x207d790 VA: 0x7594695790
	public Void SetSpriteColor(Color color) { }
	// RVA: 0x207d4a8 VA: 0x75946954a8
	private Void _ClearIfNot(Boolean keepSprite) { }
	// RVA: 0x207d5b4 VA: 0x75946955b4
	private IEnumerator _DoEnter(Action finishCb) { }
	// RVA: 0x207d69c VA: 0x759469569c
	private IEnumerator _DoLeave() { }
	// RVA: 0x207d7ec VA: 0x75946957ec
	public Void .ctor() { }
}
```