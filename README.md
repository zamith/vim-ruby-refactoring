# Ruby Refactoring Tool for Vim

I love vim! It's my editor of choice when I am developing software.

Currently (for the last 4 years at least) I have been working mainly
with the Ruby Programming Language.

I have been using ecomba/vim-ruby-reactoring for a while and there are
some things I wanted to improve. Since the project seems to be dead, I
forked it and so here we are.

The remaining README is copied from their repository.
   
## Implemented commands/patterns:
   
    :RAddParameter           - Add Parameter 
    :RInlineTemp             - Inline Temp
    :RConvertPostConditional - Convert Post Conditional
    :RExtractConstant        - Extract Constant          (visual selection)
    :RExtractLet             - Extract to Let (Rspec)
    :RExtractLocalVariable   - Extract Local Variable    (visual selection)
    :RRenameLocalVariable    - Rename Local Variable     (visual selection/variable under the cursor, *REQUIRES matchit.vim*)
    :RRenameInstanceVariable - Rename Instance Variable  (visual selection, *REQUIRES matchit.vim*)
    :RExtractMethod          - Extract Method            (visual selection, *REQUIRES matchit.vim*)

## Default bindings:

    :nnoremap <leader>rap  :RAddParameter<cr>
    :nnoremap <leader>rcpc :RConvertPostConditional<cr>
    :nnoremap <leader>rel  :RExtractLet<cr>
    :vnoremap <leader>rec  :RExtractConstant<cr>
    :vnoremap <leader>relv :RExtractLocalVariable<cr>
    :nnoremap <leader>rit  :RInlineTemp<cr>
    :vnoremap <leader>rrlv :RRenameLocalVariable<cr>
    :vnoremap <leader>rriv :RRenameInstanceVariable<cr>
    :vnoremap <leader>rem  :RExtractMethod<cr>

Additional usage examples (thanks Justin!):
[http://justinram.wordpress.com/2010/12/30/vim-ruby-refactoring-series/](http://justinram.wordpress.com/2010/12/30/vim-ruby-refactoring-series/)

## Documentation
[http://relishapp.com/despo/vim-ruby-refactoring](http://relishapp.com/despo/vim-ruby-refactoring)

Enrique Comba Riepenhausen & Paul King

