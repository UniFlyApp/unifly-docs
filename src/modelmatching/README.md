# Model Matching

UniFly's model matching aims to be compatible with vPilot's existing .vmr system documented on their website.

In particular to the UniFly implementation, when multiple model rules are relevant to an aircraft being model matched, the most specific rule wins. If there are multiple rules of equally high specificity, the winning rule will have its file name earlier in the alphabet.

Rule files are read from `%localappdata%/unifly/modelmatching`
