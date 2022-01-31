# Electromagnetic Field 2022 Site Plan

This is the master site plan for EMF 2022. It's in DXF (CAD) format, using the OSGB1938
(EPSG27700) coordinate reference system. That means that the drawing units are meters.

This map is rendered for the web using [buildmap](https://github.com/emfcamp/buildmap).

## Editing

If you need to edit the DXF, there are a few things you should be aware of:

QCAD Pro 3.24 is the recommended software. Editing *may* work in other versions of QCAD
(including the free version), but probably won't work in any other CAD software. DXF
is a bad standard.

This plan uses the DXF XDATA extension to pass data on to the mapping pipeline and other
planning tools. Some CAD software will silently discard XDATA. This makes us sad.

It's a DXF, which means it doesn't merge cleanly. Pull requests are not accepted, and we
operate a strict locking system. If you want to make a change, you must ask Russ for
the lock first, and let him know when you're done. Not doing this will result in a high
chance of your changes being irretrievably lost.

Please keep all layers locked unless you are editing them, and lock them again when you're
done.
