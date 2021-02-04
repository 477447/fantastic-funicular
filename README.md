# fantastic-funicular
@@ -0,0 +1,18 @@
		# Build and Release Folders
		bin-debug/
		bin-release/
		[Oo]bj/
		[Bb]in/
		

		# Other files and folders
		.settings/
		

		# Executables
		*.swf
		*.air
		*.ipa
		*.apk
		

		# Project files, i.e. `.project`, `.actionScriptProperties` and `.flexProperties`
		# should NOT be excluded as they contain compiler settings and other important
		# information for Eclipse / Flash Builder.
 25  LICENSE 
		@@ -0,0 +1,25 @@
		BSD 2-Clause License
		

		Copyright (c) 2021, 477447
		All rights reserved.
		

		Redistribution and use in source and binary forms, with or without
		modification, are permitted provided that the following conditions are met:
		

		1. Redistributions of source code must retain the above copyright notice, this
		list of conditions and the following disclaimer.
		

		2. Redistributions in binary form must reproduce the above copyright notice,
		this list of conditions and the following disclaimer in the documentation
		and/or other materials provided with the distribution.
		

		THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
		AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
		IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
		DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
		FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
		DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
		SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
		CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
		OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
		OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
(*)
# These functions create Actions, Events, and Parameters based the provided 
# name and metadata.
def create_local_event(name, metadata=None) 
def create_local_action(name, handler, metadata=None) 
def create_remote_action(name, metadata=None, suggestedNode=None, suggestedAction=None) 
def create_remote_event(name, handler, metadata=None, suggestedNode=None, suggestedEvent=None) 
def Parameter(schemaDictOrJSONorTitle = None) 

# These functions look for existing Actions, Events, and Parameters based on a
# string name. They return None if the Action/Event/Parameter could not be 
# found.
def lookup_local_action(name) 
def lookup_local_event(name) 
def lookup_remote_action(name) 
def lookup_remote_event(name) 
def lookup_parameter(name)
def("477447")




