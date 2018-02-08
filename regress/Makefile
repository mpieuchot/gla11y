
TESTS =	000-multiple_a11y_children \
	001-non_existing_labelled-by \
	002-multiple_label-for \
	003-multiple_mnemonic_widget \
	004-broken_label-for \
	005-broken_mnemonic_widget \
	006-empty_GtkLabel

all: $(TESTS)

$(TESTS):
	gla11y $@.ui | diff -u /dev/stdin $@.ok

.PHONY: all $(TESTS)

