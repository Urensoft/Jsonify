# Jsonify
A library for converting strings to Dictionary&lt;string,object> in c#

#1 Basic Usage:

using Urensoft.Jsonify;

Jsonify jify         = new Jsonify();
var Dictionary            = jify.JsonFromString(jsonString);
