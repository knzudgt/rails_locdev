require 'asciidoctor'

guard 'shell' do
  watch(/^.*\.adoc$/) {|m|
    Asciidoctor.convert_file m[0], safe: :safe
  }
end
