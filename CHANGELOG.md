# 0.2

Prettyprint based on the `prettyprinter` library, instead of `ansi-wl-pprint`.
To support the `Diagnostic` module, the Trifecta-generated `Doc` has to be
rendered still, so we cannot drop the dependency on ansi-wl-pprint just yet.