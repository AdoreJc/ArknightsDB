# TextGroupWithPadding

**Namespace:** ` `


## Fields

- `Int32 _rewardCountLabelAutoSizeFitLengthThreshold`

- `Single _manualSizeLength`


## Methods

- `Void Init()`

- `Void _RefreshPhaseRewardCountLabelsFitter(String)`

- `Void Setup(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TextGroupWithPadding
{
	private Text[] _labels; // 0x10
	private Single[] _stringLengthPaddingConfigs; // 0x18
	private Int32 _rewardCountLabelAutoSizeFitLengthThreshold; // 0x20
	private Single _manualSizeLength; // 0x24
	private Single[] m_labelBasicOffsets; // 0x28
	private ContentSizeFitter[] m_rewardCountContentFitters; // 0x30


	// RVA: 0x27445e4 VA: 0x7594d5c5e4
	public Void Init() { }
	// RVA: 0x27462a4 VA: 0x7594d5e2a4
	private Void _RefreshPhaseRewardCountLabelsFitter(String content) { }
	// RVA: 0x2745d98 VA: 0x7594d5dd98
	public Void Setup(String content) { }
	// RVA: 0x27464d8 VA: 0x7594d5e4d8
	public Void .ctor() { }
}
```