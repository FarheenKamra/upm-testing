<div id="foundationStructure">

<div class="section-wrapper">

<div class="container">

<div class="row">

<div class="col-sm-7">

<div class="page-heading">Prepare the foundation</div>

<div class="page-sub-heading">Here are a few rules and resources you'll need to get started.</div>

<div class="section-wrapper">

<div class="share-code">

<div class="heading">Naming your module</div>

<div class="description">UPM attempts to follow a clear naming pattern.</div>

</div>

</div>

<div class="section-description">

<div class="document-padding">

<div class="description">Modules should be sensibly named and then placed in ${libdir}/upm and headers in ${includedir}/upm.</div>

<div class="description">All modules should be prefixed with libupm-<modulename>. The upm_module_init will automatically name python UPM modules as pyupm_<modulename> and javascript modules as jsupm_<modulename>.For example for src/grove/ the library built will be libupm-grove. so, the python module pyupm_grove and the js module jsupm_grove.</div>

</div>

<div class="document-padding" style="padding-bottom: 0">

<div class="description">• Pick a name. Typically picking the name of the chip of your sensor or actuator makes the most sense. Try to pick a generic name so people with a similar sensor can inherit your class if they only have minor changes.</div>

</div>

<div class="document-padding" style="padding-bottom: 0">

<div class="description">• Use the name and stick to it.</div>

</div>

<div class="document-padding" style="padding-bottom: 0">

<div class="description">• Your lib must belong to the UPM namespace.</div>

</div>

<div class="document-padding" style="padding-bottom: 0">

<div class="description">• Avoid brand names. Often your module can be very generic with little effort.</div>

</div>

<div class="document-padding" style="padding-bottom: 0">

<div class="description">• Use only lowercase characters in your file names and folder names.</div>

</div>

</div>

</div>

</div>

</div>

</div>

<div class="section-wrapper background-theme code-sharing">

<div class="container">

<div class="row">

<div class="col-sm-7">

<div class="heading">Include a license (preferably MIT)</div>

<div class="document-padding">

<div class="description">You must license your module under a FOSS license. The recommended license is MIT but any permissive license is fine. Please consider that people using UPM may want to write proprietary programs with your sensors so we like to avoid GPL. If your license is not MIT please include a LICENSE file in src/mymodule/</div>

</div>

<div class="document-padding">

<div class="description">The top of each source file must contain a comment block containing the license information.</div>

</div>

<div class="document-padding">

<div class="description">Choosing the MIT license is preferred for the UPM repository. Below is the comment block needed at the top each source file. For your convenience, it’s here for you to cut and paste.</div>

</div>

<div class="document-padding">

<div class="permission">

<div class="description">

<div>/*</div>

<div>* The MIT License(MIT)</div>

<div>*</div>

<div>* Author: <your full name></div>

<div>* Copyright (c) <year> <copyright holder></div>

<div>*</div>

<div>* Author: <contributing author full name- if applicable></div>

<div>* Copyright (c) <year> <copyright holder></div>

<div>* Permission is hereby granted, free of charge, to any person obtaining a copy of</div>

<div>* this software and associated documentation files (the 'Software"), to deal in</div>

<div>* the Software without restriction, including without limitation the rights to</div>

<div>* use, copy, modify, merge, publisih, distribute, sublicense, and/or sell copies of</div>

<div>* the software, and to permit persons to whom tne software is furnisned to do so,</div>

<div>* subject to the following conditions:</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

<div class="section-wrapper code-sharing">

<div class="container">

<div class="row">

<div class="col-sm-7">

<div class="heading">Sign your code</div>

<div class="document-padding">

<div class="description">Each time you commit a change to your module, it must include a sign-off by everyone who authored or reviewed them.</div>

</div>

<div class="document-padding">

<div class="description">The sign-off is a simple line at the end of the explanation for the patch, which certifies that you wrote it or otherwise have the right to pass it on as an open-source patch. The rules are fairly simple if you can certify the following statement:</div>

</div>

<div class="document-padding">

<div class="description">Choosing the MIT license is preferred for the UPM repository. Below is the comment block needed at the top each source file. For your convenience, it’s here for you to cut and paste.</div>

</div>

<div class="document-padding">

<div class="permission background-theme">

<div class="description">Developer's certificate of origin 1.1</div>

<div class="description">By making a contribution to this project, I certify that:</div>

<div class="description">(a) The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file; or</div>

<div class="description">(b) the contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications. whether created in whole or in part by me, under tne same open source license (unless I am permitted to submit under a different license), as indicated in the file; or</div>

<div class="description">(c) the contribution was provided directly to me by some other person who certified (a), (b) or (c) and I have not modified it.</div>

<div class="description">(d) I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.</div>

</div>

</div>

<div class="document-padding">

<div class="description">Then you just add a line to each of your commits with --signoff saying</div>

</div>

<div class="document-padding">

<div class="permission background-theme">

<div class="description">signed-off-by: Random J developer <random@developer.example.org></div>

</div>

</div>

</div>

</div>

</div>

</div>

<div class="section-wrapper code-sharing">

<div class="container">

<div class="row">

<div class="col-sm-12"><a class="link pull-right">Create file structure ></a></div>

</div>

</div>

</div>

</div>